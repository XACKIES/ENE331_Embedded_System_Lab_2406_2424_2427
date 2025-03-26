# ENE331_Embedded_System_Lab
created by [Kittiphop Phanthachart](https://bento.me/mac-kittiphop) (a 3rd-year Engineering student)

## Introduction

This GitHub repository is dedicated to the ENE331 Embedded System Lab at KMUTT, showcasing hands-on experiments and projects that push the boundaries of embedded technology. 🚀


## Member
- 65070502406 Kittiphop Phanthachart
- 65070502424 NOPPAMIN  PIRAWATCHARAPAISARN	
- 65070502427 NIRACHA   PHOPHUANG


## HomeWork 1

### Requirement 
![a](https://github.com/XACKIES/ENE331_Embedded_System_Lab/blob/main/Doc/Screenshot%202025-03-25%20095710.png)

### Answer
[![b](https://github.com/XACKIES/ENE331_Embedded_System_Lab/blob/main/Doc/IMG_20250324_170548.jpg)](https://youtube.com/shorts/8QRXl6i8fDg?feature=share)

[Click on the image to view the result video.](https://youtube.com/shorts/8QRXl6i8fDg?feature=share)



The prescaler (PSC) can be calculated using the following equation:

$$
PSC = \frac{f_{\text{ClockSpeed}}}{f_{\text{Timer}} \times (ARR+1)} - 1 = \frac{72,000,000}{\left(\frac{1}{20 \times 10^{-6}}\right) \times (1+1)} - 1= 719
$$



Where:  
- $$f_{\text{ClockSpeed}}$$ is the APB1 timer clock frequency (Hz)  
- $$f_{\text{Timer}}$$ is the desired update event frequency (Hz)  
-  ARR   is the Auto-Reload Register value  

#### *** [ENE331_HW1_File](https://github.com/XACKIES/ENE331_Embedded_System_Lab/tree/main/HW1) ***
