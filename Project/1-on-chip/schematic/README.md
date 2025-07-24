# Simulation Result
## Ring VCO
### MVP for 50MHz
<img width="1524" height="826" alt="image" src="https://github.com/user-attachments/assets/01d392c3-4c80-4ec4-a77c-44710ab356cd" />

This is a 5 stage current starved with DC 3.3V VDD as power source.

<img width="586" height="485" alt="image" src="https://github.com/user-attachments/assets/070049fb-1d4b-449f-ad58-8241cb149fa5" />

Analysis:
* The Vth n = 0.73V and Vth p = -0.61V
* Considering the Vth then the tuning range of Vctrl is between 0.73V - 2.69V
* In the simulation he Vctrl tuning range is 0.837V - 3V
* The Oscillator reaches 50MHz when Vctrl = 1.03V
* Frequency tuning range = 13.5MHz - 275MHz
* **Needs frequency spectrum analysis for deeper analysis**

<img width="587" height="489" alt="image" src="https://github.com/user-attachments/assets/de2515f0-d995-43f2-956d-31ee8816a619" />

Vctrl = 1.03V f = 50MHz

<img width="587" height="489" alt="image" src="https://github.com/user-attachments/assets/b861bc38-9d30-47e7-81ce-168b54598519" />

Vctrl = 3V (Very noisy) f = 275MHz

<img width="587" height="489" alt="image" src="https://github.com/user-attachments/assets/2f8eac0d-1f81-4ce9-9dd7-81e099af68f8" />

Vctrl = 0.837V f =13.5MHz
