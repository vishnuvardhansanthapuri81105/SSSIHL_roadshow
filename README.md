SSSIHL_ROADSHOW

Dr. Kunal Ghosh and his team conducted a one-day workshop on VLSI and RISC-V chip designing roadshow. During the workshop, we learned about different types of chips, microprocessors, and microcontrollers. They explained the process of chip designing and provided insights into how chips are designed and categorized. For designing a chip, we used VirtualBox and VS Code, along with Platform IO and Python in VS Code.

The steps of designing a chip are as shown below in the screenshots:

![Screenshot 2024-12-13 100212](https://github.com/user-attachments/assets/e43f5997-95ca-4484-9d86-2051a5b7ca32)

![Screenshot 2024-12-13 101350](https://github.com/user-attachments/assets/96eb982b-7500-45e6-a4f0-100d3f85842b)

Then we  wrote a code which is  shown below and saved as (filename.c)

CODE:

![Screenshot 2024-12-17 203617](https://github.com/user-attachments/assets/a369523d-7a00-41d5-831f-74ef01504004


![Screenshot 2024-12-13 102746](https://github.com/user-attachments/assets/807291f2-df8b-4cab-a3a9-44d0a9240263)


![Screenshot 2024-12-13 105337](https://github.com/user-attachments/assets/32e64fdc-40c2-4f3b-9334-cabf88118c90)


![Screenshot 2024-12-13 121213](https://github.com/user-attachments/assets/10483876-c7c2-42f9-bfb6-10a733e0e113)


![Screenshot 2024-12-13 121757](https://github.com/user-attachments/assets/183e7259-7012-45ba-a886-9bfe3b49a448)


![Screenshot 2024-12-13 121915](https://github.com/user-attachments/assets/17d7a9f0-9450-4b54-9571-15f2c78e1bfd)


Then we entered the following command: run_synthesis

![Screenshot 2024-12-13 122545](https://github.com/user-attachments/assets/ceef6e82-0a3a-4daf-8c34-d24c0e369a0e)


Then we entered the command : run_floorplan

![Screenshot 2024-12-13 123713](https://github.com/user-attachments/assets/d6571585-6682-4437-9b34-4ae21b77599f)


![Screenshot 2024-12-13 123743](https://github.com/user-attachments/assets/9e425eb5-8383-40e9-a1ab-9a8fc9cad183)


we get a Floorplan image by using a command in a new tab:

" eog designs/picorv32a/runs/(press tab)/results/floorplan/picorv32a.floorplan.def.png"

![Screenshot 2024-12-13 124151](https://github.com/user-attachments/assets/804fbeb6-766e-4e22-ad87-152101884336)


![Screenshot 2024-12-13 124245](https://github.com/user-attachments/assets/437ac2ea-aac2-4d2b-a559-fb4734a6cb9d)


![Screenshot 2024-12-13 140643](https://github.com/user-attachments/assets/6c824897-dd03-4545-9ccc-ce779e95d7a6)


Then we get a placement image by using the command in a new tab:

"eog designs/picorv32a/runs/(press tab)/results/placement/picorv32a.placement.def.png"


![Screenshot 2024-12-13 141427](https://github.com/user-attachments/assets/5e612783-4fd1-44cd-89a2-770cd0d06245)


![Screenshot 2024-12-13 141714](https://github.com/user-attachments/assets/2dfc4d90-d9dc-4a71-a764-5b0f2b892419)


Then we entered the command "run_cts"

![Screenshot 2024-12-13 141850](https://github.com/user-attachments/assets/21bb69d3-89cc-47c8-bcd1-0bf561d165e9)


![Screenshot 2024-12-13 142010](https://github.com/user-attachments/assets/ff3cd47b-32dd-428d-b61c-434423b5b5f2)


Entered a command "run_rerouting"

![Screenshot 2024-12-13 143312](https://github.com/user-attachments/assets/e39fe0b1-9e68-4260-b8bc-eec9bd068d05)


![Screenshot 2024-12-13 144355](https://github.com/user-attachments/assets/a75270a4-d7cb-49ef-9f4d-38d580d282a0)



At last we got Boards to run the code and check whether it is working or not.
So, by using VS Code (VISUAL STUDIO CODE), we added Platform IO extension and entered the code.
the code is shown below:


![Screenshot 2024-12-17 205444](https://github.com/user-attachments/assets/a9b784a9-8aec-4e30-943a-f41c95ae939a)


we then Build the code, after that we uploaded the code, then the light in the board started blinking.
the blinking video was shown below.


https://github.com/user-attachments/assets/64ad60ba-212f-41e5-82ab-10632dac0d72

We then again used a different code to set the light only to fadeout insteading of blinking.
The video was shoen below:



https://github.com/user-attachments/assets/7b6f57dd-2cc0-4a83-9567-6fbbe3a1d147

This workshop, which we attended as a department, was extremely helpful and provided us with valuable insights into VLSI and chip designing. I would like to express my gratitude to Mr. Kunal Ghosh and his team for teaching us and providing the necessary equipment for the workshop. I would also like to thank our institute and department for giving us this wonderful opportunity.

