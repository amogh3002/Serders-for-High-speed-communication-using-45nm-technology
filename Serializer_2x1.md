Serializer_2x1

A 2×1 serializer converts 2 parallel input bits into 1 serial output bit stream. It is commonly implemented using two storage elements and a 2:1 multiplexer (MUX).

<img width="1484" height="746" alt="Screenshot 2026-10-11 102911" src="https://github.com/user-attachments/assets/8c5b9783-3640-4a7a-b41d-6292dff08a8c" />

The basic circuit consists of:
- Two D flip-flops: Store the two parallel input bits \(D_0\) and \(D_1\).
- One 2:1 MUX: Selects which stored bit reaches the output.
- Select signal (Sel): Controls the MUX.
- Clock (CLK): Controls when the input data is captured.

The MUX output is given by:

<img width="258" height="54" alt="image" src="https://github.com/user-attachments/assets/9c371e23-0ec1-4fc7-9e62-0286ec029aa0" />


Serializer_2x1 Testbench

<img width="1306" height="783" alt="image" src="https://github.com/user-attachments/assets/8b500f74-0007-4422-acb6-ca589888ce5d" />

PreLayout simulation

<img width="1372" height="798" alt="image" src="https://github.com/user-attachments/assets/a4ab8ce1-7854-49f2-8f5d-5677c7febed0" />

Layout of Serializer_2x1

<img width="1165" height="684" alt="image" src="https://github.com/user-attachments/assets/ba8316f5-0e9d-4d9e-a617-474f113656a7" />




