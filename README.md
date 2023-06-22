# Expert-System-Medical-Diagnosis

## Demo

*Questions asked to the bot*
![Questions](https://github.com/bhavesh-kharat/Expert-System-Medical-Diagnosis/assets/54846652/5f54be32-b469-4c72-8d0e-1f78df803fbe)

*Preventive Measures suggested by the bot*
![DiseaseSolution1](https://github.com/bhavesh-kharat/Expert-System-Medical-Diagnosis/assets/54846652/703e8d07-6d7f-49ed-86a9-80eb20029063)

![DiseaseSolution2](https://github.com/bhavesh-kharat/Expert-System-Medical-Diagnosis/assets/54846652/6303c295-6707-4462-a7c9-00823c0b4759)

## What is Expert System 
![Expert System](https://github.com/bhavesh-kharat/Expert-System-Medical-Diagnosis/assets/54846652/107ceccc-ef6d-4afd-ad5b-5e648b5c0aa3)

### Examples for Expert System
- Spell Checker
- Support chat application

## Summary

Typical expert systems use knowledge to reason about input data and produce meaningful results. Create a knowledge-base expert system that will provide patients with medical advice and fundamental disease understanding. It should analyse numerous symptoms and indicators such as chest pain, cough, fainting, exhaustion, headache, back pain, sunken eyes, low body temperature, restlessness, sore throat, fever, and so on, as well as its severity status, and provide medical advise to patients.


#### Features:
- Experta (*pyknow earlier*),a Python library is used as the core.
- The engine asks the user for 11 different symptoms.
- The user types *yes* or *no* to each symptom.
- The engine tries to determine the disease based on the user's responses and predefined rules.
- Once the disease is found, a detailed explanation regarding the disease and treatments are shown to the user.
- If the symptom does not match a particular disease, the disease matching the highest number of symptoms is displayed to the user.


**Note: This project is just for demonstration purposes. The symptoms and diseases are likely to not match. It is an attempt to showcase how powerful these basic systems can get. Please do not use for any medical advice.**

## Installation
Python3 needs to be installed in your system.

**For installing _experta_:**
```bash
$ sudo pip3 install experta
```

**For running the main file use:**

```bash
$ python3 medical_expert_system.py
```


## Authors

**[Bhavesh Kharat]([https://github.com/bhavesh-kharat])**


## References
- [Experta](https://pypi.org/project/experta/)
