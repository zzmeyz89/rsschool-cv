<img src="ProfilePhotoPlaceholder.PNG" alt="Applicant photo" height="200">

## Aliaksandr Kharchanka

Discord: zzmeyz89 (@zzmeyz89)  
E-mail: <zzmeyz@mail.ru>

### **SUMMARY**

Open mind and fast learning person.  Ability to think analytically and to look at problems from different angles. Accuracy and pedantry. Ready to a new knowledges and skills. 

### **SKILLS**

- Developing working process 
- Resource management
- Factory acceptance tests of a process automation equipment
- Documentation designing and translation
- Interactions and communications with contractors
- Equipment maintenance and repair
- Industrial automation equipment programming
- Developing working process
- Self-studying JavaScript, NodeJS, Git, HTML, CSS, including RS-preschool
- English level B1

**Certificates:** Festo “Siemens CPU programming”, Festo “Siemens CPU programming. STEP7-INTERM”

**Software skills:** Microsoft Windows, Microsoft Office (Word, Excel), Photoshop, AutoCAD, VMware, VirtualBox, SIMATIC Step7, PCS7, WinCC, Visual Studio Code

### **EDUCATION**

1.	Radio electronics engineer (specialist), Automation and Information Systems Faculty, Gomel State Technical University, Gomel, Belarus, 2015
2.	Master of Engineering Science, Automation and Information Systems Faculty, Gomel State Technical University, Gomel, Belarus, 2018
3.	Master in Logistics, Faculty of Economics and Law, International University “MITSO”, Gomel, Belarus, 2020

### **WORK EXPERIENCE**

June 2015 till now  
**Dobrush Paper Factory "Geroy Truda"**, process automation lead engineer

### **CODE SAMPLE**

```js
function getCard() {
  const arrB = createRow('B', 1, 15, 5);
  const arrI = createRow('I', 16, 30, 5);
  const arrN = createRow('N', 31, 45, 4);
  const arrG = createRow('G', 46, 60, 5);
  const arrO = createRow('O', 61, 75, 5);
  return arrB.concat(arrI, arrN, arrG, arrO);
}

function createRow (row, min, max, quant) {
  let result = [];
  for (let i = 0; i < quant; i++) {
    let number = Math.floor(Math.random() * (max - min)) +min;
    if (result.indexOf(row + number) === -1) {
      result.push(row + number);
    } else {
      --i;
    }
  }
  return result;
}
  ```

### **PROJECTS**

CV for RS-School:  
<https://github.com/zzmeyz89/rsschool-cv>

Memory-game:  
<https://rolling-scopes-school.github.io/zzmeyz89-JSFEPRESCHOOL/memory-game>
