# Buck-LDO Regulator-5V-3A-3.3V-1.5A
</br>This project features a high performance Dual Rail Power Supply providing a low-noise voltage source. The 3.3V/1.5A output is ideal for sensors as it is regulated through an LDO which gives a low noise voltage source. The 5V/3A output is suitable for power supply to MCUs and general logic. It is highly recommended to add extra electrolytic capacitors to the output to prevent voltage drops and ensure a more stable power environment.
* **INPUT** : 8V-25V 
* **OUTPUT** : 5V/3A, 3.3V/1.5A (Total output current must not exceed 3A)

<img width="1284" height="909" alt="Screenshot 2026-03-28 182112" src="https://github.com/user-attachments/assets/aeee4c78-fa44-44fb-959d-fae6fde7315d" /></br>

<img width="1189" height="732" alt="Screenshot 2026-03-28 180529" src="https://github.com/user-attachments/assets/084edf87-64e3-48c5-8cb9-2a4b3e42b7ab" /></br>
</br>The design is based on both manufacturer's datasheet, with the output voltage from being simulated in stages using **Pspice for TI for the TPS54302** and **LTspice for the LT1963**. This separate approach was taken because the TPS54302 and the LT1963 models are not compatible with each over the same simulation environment at the same time.</br>

<img width="1919" height="1079" alt="Screenshot 2026-03-28 184607" src="https://github.com/user-attachments/assets/4ee68e78-8e4e-4d8f-9ba7-83eae4817494" />
</br>
</br>
<img width="1919" height="909" alt="Screenshot 2026-03-28 191828" src="https://github.com/user-attachments/assets/0fe0630b-77c7-4d1c-87d2-eab0351625ed" />

