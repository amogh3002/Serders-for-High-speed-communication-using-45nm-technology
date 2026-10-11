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

