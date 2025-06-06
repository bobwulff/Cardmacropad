# Cardmacropad
If you're reading this, I probably handed you a business card at some point. Oh it was so nice to meet you probably! Lets turn that business card into something useful, like a keyboard macropad.
<br><br>
<img width="959" alt="image" src="https://github.com/user-attachments/assets/8809f8bc-3516-4df1-bf93-5fd57bdb9574" />

You can also purchase [your own PCB here if you'd like](https://www.pcbway.com/project/shareproject/Macro_Pad_Card_999fac36.html)
<br><br>

# COMPONENTS REQUIRED:
| Component | Recommended Link | Alt Link |
| ------------- | ------------- | ------------- |
| RP2040 Zero | [Aliexpress](https://s.click.aliexpress.com/e/_okoF943) | [Amazon](https://amzn.to/3ZdtdvE) |
| 6x6x4.3 Tactile Push Button Switches | [Aliexpress](https://s.click.aliexpress.com/e/_oEwUhSf) | [Amazon](https://amzn.to/3GMue7G) |
| Kailh Low Profile Choc Switches | [Aliexpress](https://s.click.aliexpress.com/e/_onZQ1ER) | [Amazon](https://amzn.to/3ZcWPtb) |

![Screenshot 2025-05-07 18-41-26](https://github.com/user-attachments/assets/fee73c79-86c1-4003-9ce5-e7100ba2b9f1)

# OPTIONAL:
| Component | Recommended Link | Alt Link |
| ------------- | ------------- | ------------- |
| Kailh Low Profile Hot-swappable PCB Socket | [Aliexpress](https://s.click.aliexpress.com/e/_oFkTKZv) | [Amazon](https://amzn.to/44trzcY) |
| Low Profile Keycaps | [Aliexpress](https://s.click.aliexpress.com/e/_oorbBj1) | [Amazon](https://amzn.to/42BwSVh) | 

<img width="33%" alt="image" src="https://github.com/user-attachments/assets/6166fe2a-0523-43f8-b454-d66db0804f29" />
<img width="33%" alt="image" src="https://github.com/user-attachments/assets/7cc85317-1e44-46dc-a575-82b3483d6a3c" />
<img width="33%" alt="image" src="https://github.com/user-attachments/assets/3f97d2c7-7092-4075-8b6c-c8494174ae86" />


# GET YOUR TOOLS READY

• USB-C cable <br>
• Soldering Iron <br>
• Solder <br>
• A safe surface to solder on <br>

![Screenshot 2025-05-07 18-46-08](https://github.com/user-attachments/assets/a1b1d15f-75e1-4723-b4e6-0bbb79d322fe)

# START THE ASSEMBLY

1) Place the PI-Zero flat onto the PCB and solder two of the corners for stability. When soldering, I would recommend melting the solder onto the exposed contact on the PCB, then dragging it onto the PI-Zero's contacts with the soldering iron <br><br>
![Screenshot 2025-05-07 18-48-15](https://github.com/user-attachments/assets/5f0c989f-eda8-4d8d-b280-e6a87d48ceab)

2) Solder the rest of the PI-Zero's contacts onto the board <br><br>
![Screenshot 2025-05-07 18-51-00](https://github.com/user-attachments/assets/f94f2fd9-ca0b-4aed-930d-0c122610d875)

3) Place the tact switches through the holes on the board <br><br>
![Screenshot 2025-05-07 18-53-31](https://github.com/user-attachments/assets/ae63d5f8-ad41-4cdc-9c93-77daac0ec4a3)

4) Flip the board around and bend the pins of the switches so they are flat and stay in place (it helps to use a flat metal tool, or a coin) <br><br>
![Screenshot 2025-05-07 18-53-42](https://github.com/user-attachments/assets/776911bc-0157-46c4-9752-d39bf57ad532)

5) Solder the tact switches from the back (dont be afraid to glob that solder on and through the hole) <br><br>
![Screenshot 2025-05-07 18-58-16](https://github.com/user-attachments/assets/4c027d0a-3316-49a3-b670-e4e442b8682e)

6) Deside whether or not youre going to use hotswap sockets or just solder the switches in place <br><br>
![Screenshot 2025-05-07 18-59-36](https://github.com/user-attachments/assets/02aa8e02-fc73-4b6b-8210-e5618ceb6d4e)

7) If soldering the switches in place, just pop those suckers in. Make sure the metal pins of the switches are through the small silver holes <br><br>
![Screenshot 2025-05-07 19-01-10](https://github.com/user-attachments/assets/2b66fdb0-96c8-4a4b-b873-a4cd12aace27)
![Screenshot 2025-05-07 19-01-20](https://github.com/user-attachments/assets/f4cba103-47b8-4ff0-9b9c-d039dedc8db1)
![Screenshot 2025-05-07 19-01-54](https://github.com/user-attachments/assets/4ffbf8c6-1ce0-4ee9-90f4-b7f0acccb71c)
![Screenshot 2025-05-07 19-02-04](https://github.com/user-attachments/assets/ab62f474-ed9d-44a8-90bc-2003be3472ed)

8) Flip the board over and solder the metal pins on the back (GLOB IT ON). Do NOT solder the plastic nubs (seen in red here) <br><br>
![Screenshot 2025-05-07 19-04-22](https://github.com/user-attachments/assets/82997645-4072-47d6-8bdb-13899ea26203)

# Congrats! You have completed the assembly
![Screenshot 2025-05-07 19-04-55](https://github.com/user-attachments/assets/2be355cb-5ddb-4403-ae32-4a835e5dc8f3)

# NOW FOR THE FIRMWARE

1) Connect the macropad to a computer with a USB-C cable WHILE HOLDING the BOOT button on the PI-Zero. <br><br>
![Screenshot 2025-05-07 19-07-53](https://github.com/user-attachments/assets/fec8fff5-d5cd-4f77-b5ac-f1f2fcd09a04)

2) If done correctly, it will show up as a drive on your computer. If this does not happen, hold the BOOT button, and while holding the BOOT button press the RESET button one time. <br><br>
![Screenshot 2025-05-07 19-09-08](https://github.com/user-attachments/assets/a632cb60-43d0-4080-942b-c036f9c10f16)

3) Drag over the [GP2040-CE_0.7.11_WaveshareZero.uf2 firmware linked here](https://github.com/bobwulff/Cardmacropad/blob/ba1f3849e7113883848c1dc979786deaaa10a982/GP2040-CE_0.7.11_WaveshareZero.uf2) <br><br>
![Screenshot 2025-05-07 19-38-28](https://github.com/user-attachments/assets/44e7905f-b5d7-4695-ab37-40e06e13e0b4)

4) Allow the device to completely reboot. To test if this worked, head over to [gamepadtester](https://hardwaretester.com/gamepad) and press some buttons <br><br>
![Screenshot 2025-05-07 19-12-37](https://github.com/user-attachments/assets/15ea31e5-c13b-440c-b678-741d9530a0d3)

# Congrats, you now have an X-input controller. But lets make it a keyboard.

1) Hold the SW5 button (bottom right tact switch) and press the RESET button one time. <br><br>
![Screenshot 2025-05-07 19-39-52](https://github.com/user-attachments/assets/61e69281-5e69-42cf-aaaa-450de9b8a4b5)

2) Next, head to http://192.168.7.1 in a web browser <br><br>
![Screenshot 2025-05-07 19-40-35](https://github.com/user-attachments/assets/ce938147-1482-4a9d-b2ce-24aed6181f5f)

3) Click CONFIGURATION > Data Backup and Restoration <br><br>
![Screenshot 2025-05-07 19-16-32](https://github.com/user-attachments/assets/d69d10fa-bacc-426d-ba04-27f8af04d8c9)

4) Load [WDnumpad_ZERO.gp2040 found here](https://github.com/bobwulff/Cardmacropad/blob/ba1f3849e7113883848c1dc979786deaaa10a982/WDnumpad_ZERO.gp2040) <br><br>
![Screenshot 2025-05-07 19-18-14](https://github.com/user-attachments/assets/550941a7-ce9d-42df-9942-d4d33ea62516)

5) Look at the top right corner of the web-page and change this dropdown to GENERIC <br><br>
![Screenshot 2025-05-07 19-20-32](https://github.com/user-attachments/assets/58fce706-93e0-4888-b1d7-04615ef1f2af)

6) Head to SETTINGS > INPUT MODE > and change inputs 1-10 to be your desired buttons. Below is an example of what I have mine set to. When you're done, make sure to click SAVE at the bottom and then REBOOT in the top right corner. <br><br>
<img width="993" alt="image" src="https://github.com/user-attachments/assets/4898eea9-0fad-4c62-9569-310b63b0b542" />

7) Here is a map of what each button will be labeled as in the GP2040 keyboard mapping page (you want to look at the GENERIC column). Feel free to map each button to whatever you'd like <br><br>
![image](https://github.com/user-attachments/assets/9f7936fc-cc1c-4653-a046-603371a32c1b)

8) If at this point you run into any issues, head over to the "GPIO Pin Mapping" page and click "GPIO Pin viewer" to see if the buttons work and what they are currently mapped to. You can also use this page to re-map them if need be.

# SUCCESS!!! You now have a MACROPAD!

3D printable case coming soon.... <br><br>
<img width="953" alt="image" src="https://github.com/user-attachments/assets/01fdb359-1e46-43b4-9de2-70ca8137c4ed" />



