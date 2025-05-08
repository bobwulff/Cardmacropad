# Cardmacropad
If you're reading this, I probably handed you a business card at some point. Oh it was so nice to meet you whoever you are! Lets turn that business card into something useful, like a keyboard macropad.
<img width="959" alt="image" src="https://github.com/user-attachments/assets/8809f8bc-3516-4df1-bf93-5fd57bdb9574" />

# COMPONENTS REQUIRED:
| Component | Link |
| ------------- | ------------- |
| RP2040 Zero | [Aliexpress](https://s.click.aliexpress.com/e/_okoF943) |
| 6x6x4.3 Tactile Push Button Switches | [Aliexpress](https://s.click.aliexpress.com/e/_oBOFdpZ) |
| Kailh Low Profile Choc Switches | [Aliexpress](https://s.click.aliexpress.com/e/_opeXaZt) |

![Screenshot 2025-05-07 18-41-26](https://github.com/user-attachments/assets/fee73c79-86c1-4003-9ce5-e7100ba2b9f1)

# OPTIONAL:
| Component | Link |
| ------------- | ------------- |
| Kailh Low Profile Hot-swappable PCB Socket | [Aliexpress](https://s.click.aliexpress.com/e/_oFkTKZv) |
| Low Profile Keycaps | [Amazon](https://amzn.to/42BwSVh) |

![Screenshot 2025-05-07 18-43-35](https://github.com/user-attachments/assets/6166fe2a-0523-43f8-b454-d66db0804f29)
![Screenshot 2025-05-07 18-43-49](https://github.com/user-attachments/assets/7cc85317-1e44-46dc-a575-82b3483d6a3c)
<img width="961" alt="image" src="https://github.com/user-attachments/assets/3f97d2c7-7092-4075-8b6c-c8494174ae86" />


# GET YOUR TOOLS

![Screenshot 2025-05-07 18-46-08](https://github.com/user-attachments/assets/a1b1d15f-75e1-4723-b4e6-0bbb79d322fe)

# START THE ASSEMBLY

1) Place the PIzero and solder two of the corners for stability. I would recommend placing the solder on the PCB portion and dragging it onto the PIzero
![Screenshot 2025-05-07 18-48-15](https://github.com/user-attachments/assets/5f0c989f-eda8-4d8d-b280-e6a87d48ceab)

2) Solder the rest of the pizero's contacts onto the board
![Screenshot 2025-05-07 18-51-00](https://github.com/user-attachments/assets/f94f2fd9-ca0b-4aed-930d-0c122610d875)

3) Place the tact switches through the holes on the board
![Screenshot 2025-05-07 18-53-31](https://github.com/user-attachments/assets/ae63d5f8-ad41-4cdc-9c93-77daac0ec4a3)

4) Flip the board around and bend the pins of the switches so they are flat and stay in place (it helps to use a flat metal tool, or a coin)
![Screenshot 2025-05-07 18-53-42](https://github.com/user-attachments/assets/776911bc-0157-46c4-9752-d39bf57ad532)

5) Solder the tact switches from the back (dont be afraid to glob that solder on and through the hole)
![Screenshot 2025-05-07 18-58-16](https://github.com/user-attachments/assets/4c027d0a-3316-49a3-b670-e4e442b8682e)

6) Deside whether or not youre going to use hotswap sockets or just solder the switches in place
![Screenshot 2025-05-07 18-59-36](https://github.com/user-attachments/assets/02aa8e02-fc73-4b6b-8210-e5618ceb6d4e)

7) If soldering the switches in place, just pop those suckers in. Make sure the metal pins of the switches are through the small silver holes
![Screenshot 2025-05-07 19-01-10](https://github.com/user-attachments/assets/2b66fdb0-96c8-4a4b-b873-a4cd12aace27)
![Screenshot 2025-05-07 19-01-20](https://github.com/user-attachments/assets/f4cba103-47b8-4ff0-9b9c-d039dedc8db1)
![Screenshot 2025-05-07 19-01-54](https://github.com/user-attachments/assets/4ffbf8c6-1ce0-4ee9-90f4-b7f0acccb71c)
![Screenshot 2025-05-07 19-02-04](https://github.com/user-attachments/assets/ab62f474-ed9d-44a8-90bc-2003be3472ed)

8) Flip the board over and solder the holes on the back (GLOB IT ON)
![Screenshot 2025-05-07 19-04-22](https://github.com/user-attachments/assets/82997645-4072-47d6-8bdb-13899ea26203)

# Congrats! You have completed the assembly
![Screenshot 2025-05-07 19-04-55](https://github.com/user-attachments/assets/2be355cb-5ddb-4403-ae32-4a835e5dc8f3)

# NOW FOR THE FIRMWARE

1) Connect the macropad to a computer with a USB-C cable WHILE HOLDING the BOOT button on the PiZero.
![Screenshot 2025-05-07 19-07-53](https://github.com/user-attachments/assets/fec8fff5-d5cd-4f77-b5ac-f1f2fcd09a04)

2) If done correctly, it will show up as a drive on your computer. If this does not happen, hold the BOOT button, and while holding the BOOT button and press the RESET button one time.
![Screenshot 2025-05-07 19-09-08](https://github.com/user-attachments/assets/a632cb60-43d0-4080-942b-c036f9c10f16)

3) Drag over the [GP2040-CE_0.7.11_WaveshareZero.uf2 firmware linked here](https://github.com/bobwulff/Cardmacropad/blob/ba1f3849e7113883848c1dc979786deaaa10a982/GP2040-CE_0.7.11_WaveshareZero.uf2)
![Screenshot 2025-05-07 19-38-28](https://github.com/user-attachments/assets/44e7905f-b5d7-4695-ab37-40e06e13e0b4)

4) Allow the device to completely reboot. To test if this worked, head over to [gamepadtester](https://hardwaretester.com/gamepad) and press some buttons
![Screenshot 2025-05-07 19-12-37](https://github.com/user-attachments/assets/15ea31e5-c13b-440c-b678-741d9530a0d3)

# Congrats, you now have an X-input controller. But lets make it a keyboard.

1) Hold the SW5 button (bottom right tact switch) and press the RESET button one time.
![Screenshot 2025-05-07 19-39-52](https://github.com/user-attachments/assets/61e69281-5e69-42cf-aaaa-450de9b8a4b5)

2) Next, head to (http://192.168.7.1)[http://192.168.7.1] in a web browser
![Screenshot 2025-05-07 19-40-35](https://github.com/user-attachments/assets/ce938147-1482-4a9d-b2ce-24aed6181f5f)

3) Click CONFIGURATION > Data Backup and Restoration
![Screenshot 2025-05-07 19-16-32](https://github.com/user-attachments/assets/d69d10fa-bacc-426d-ba04-27f8af04d8c9)

4) Load [WDnumpad_ZERO.gp2040 found here](https://github.com/bobwulff/Cardmacropad/blob/ba1f3849e7113883848c1dc979786deaaa10a982/WDnumpad_ZERO.gp2040)
![Screenshot 2025-05-07 19-18-14](https://github.com/user-attachments/assets/550941a7-ce9d-42df-9942-d4d33ea62516)

5) Look at the top right corner of the web-page and change this dropdown to GENERIC
![Screenshot 2025-05-07 19-20-32](https://github.com/user-attachments/assets/58fce706-93e0-4888-b1d7-04615ef1f2af)

6) Head to SETTINGS > INPUT MODE > and change inputs 1-10 to be your desired buttons. Below is an example of what I have mine set to.
<img width="993" alt="image" src="https://github.com/user-attachments/assets/4898eea9-0fad-4c62-9569-310b63b0b542" />

7) Here is a map of what each button will be labeled as in the GP2040 keyboard mapping (the GENERIC column). Feel free to map each button to whatever you want
![Screenshot 2025-05-07 19-43-10](https://github.com/user-attachments/assets/2a16a6ae-4a37-4ebc-a544-a8efe78fdfd7)

# SUCCESS!!! You now have a MACROPAD!

3D printable case coming soon....
<img width="953" alt="image" src="https://github.com/user-attachments/assets/01fdb359-1e46-43b4-9de2-70ca8137c4ed" />



