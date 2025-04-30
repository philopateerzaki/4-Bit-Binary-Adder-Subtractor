# 4-Bit Binary Adder/Subtractor

This project demonstrates a 4-bit binary adder/subtractor circuit implemented using digital logic ICs. The design performs both addition and subtraction of 4-bit binary numbers by using basic hardware components, making it ideal for educational purposes in digital electronics and computer engineering.

## 🔧 Components Used
- **7483** – 4-bit Binary Full Adder
- **7486** – XOR Gate (for 2’s complement logic)
- **7408** – AND Gate
- **7432** – OR Gate (used for overflow detection)
- **7448** – BCD to 7-Segment Decoder
- **Switches** – For manual binary input (A0–A3, B0–B3)
- **7-Segment Displays** – To visualize the result

## ⚙️ How the Circuit Works
- **Input Processing:** Two 4-bit binary numbers A and B are entered using switches.
- **Addition/Subtraction Control:** A control bit (K) determines the operation. If K = 0, the circuit performs A + B. If K = 1, it performs A – B using 2's complement logic via XOR gates.
- **Cascaded Adders:** Four full adders are cascaded, with the carry-out of one connected to the carry-in of the next.
- **Output Display:** The final result is shown on a 7-segment display, and overflow can be monitored using OR logic.

## 🧠 Block Diagram
1. XOR gates for input control  
2. 4-bit adder (7483)  
3. AND/OR gates for carry and overflow  
4. Decoder and display section

## ✅ Advantages
- Pure hardware design — no programming required  
- Efficient and scalable digital logic implementation  
- Excellent for educational and prototyping use  
- Low power and compact design

## ⚠️ Limitations
- Limited to 4-bit operations  
- No dynamic signed number handling  
- No overflow flag output  
- Manual inputs may not suit real-time applications

## 🎯 Applications
- Fundamental component of ALUs  
- Digital design lab projects  
- Logic circuit demonstration and testing  
- Foundation for extended-bit arithmetic designs

## 📷 Images & Simulation
See the full report for the **Proteus schematic**, **block diagram**, and **circuit simulation screenshots**.

## 📄 Report
[Download Full Report (PDF)](insert_your_drive_or_github_link_here)
