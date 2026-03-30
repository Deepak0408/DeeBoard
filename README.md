Thia is a custom macropad which have 15 keys and one encoder
made for easy workflow 
it contain 2 small LED

Each key have its own function to perform
the encoder helps to adjust the valume accoring to use

Made this project for speedup my task


## Build Journal

### Day 1

I started this project with the idea of building a small macropad for shortcuts. At first I was not fully sure about the exact design, but I had a rough idea. I spent time looking at other macropad builds to understand how they work and what components are needed.

### Day 2

I started working on the circuit design. I tried to understand how switches and diodes are connected in a. It was a bit confusing in the beginning and I had to check multiple references. After some time I was able to make a basic schematic.

### Day 3

I moved to PCB design. This doing proper PCB, so it took longer than expected. Placing components and routing tracks was not easy and I had to redo some parts because spacing was not correct.

### Day 4

I worked on the CAD design for the case. I wanted the macropad to look clean and compact. The first design was not fitting properly, so I had to adjust dimensions and rework it. After few tries I got a better layout.

### Day 5

I started working on the firmware. I used some reference code and tried to modify it according to my design. At first nothing worked properly and it was a bit frustrating. Understanding key mapping and inputs took time.

### Day 6

Debugging took most of the time today. Some keys were not responding correctly and I thought it was hardware issue, but later I found mistakes in the code. After fixing small issues, things started working.

### Day 7

I tested the full setup and checked all inputs. The rotary encoder and LEDs were also tested. There were still small issues but overall it was working as expected.


<img width="893" height="869" alt="image" src="https://github.com/user-attachments/assets/3df1cd2d-77a6-422e-a01d-52e0826c00b5" />
<img width="826" height="953" alt="image" src="https://github.com/user-attachments/assets/9e4ce18a-73aa-4e63-a8b8-795eb2fdc55c" />


<img width="852" height="437" alt="Screenshot 2026-03-10 223859" src="https://github.com/user-attachments/assets/e7ff8bd3-4249-4b92-9033-9eb4e7b72c64" />
<img width="1124" height="679" alt="Screenshot 2026-03-10 223038" src="https://github.com/user-attachments/assets/d1843b13-bc98-4068-9bd6-70c685264001" />
<img width="1028" height="738" alt="Screenshot 2026-03-10 223014" src="https://github.com/user-attachments/assets/46830ce8-b074-4757-bd42-456f2f808280" />
<img width="1282" height="546" alt="Screenshot 2026-03-10 220041" src="https://github.com/user-attachments/assets/375b9c08-52ce-4f7d-9bad-d4e809c9e86a" />
<img width="839" height="623" alt="Screenshot 2026-03-10 223113" src="https://github.com/user-attachments/assets/539d500e-f8d9-4a46-928b-3edfd37225a5" />
<img width="682" height="429" alt="image" src="https://github.com/user-attachments/assets/548a71b6-c8ad-4e3e-b639-a62048b0e1e6" />



## Bill of Materials (BOM)

| Component                  | Purpose            | Quantity | Price (USD) | Source |
|---------------------------|-------------------|----------|------------|--------|
| SK6812 Mini RGB LED       | LED lighting      | 2        | 9.18       | Robu   |
| Rotary Encoder (with switch) | Volume control | 1        | 2.24       | Amazon |
| 1N4148 Diodes             | Signal control    | 1        | 3.08       | Amazon |
| MX Mechanical Switches    | Key input         | 1        | 18.14      | Amazon |
| XIAO RP2040 Controller    | Main controller   | 1        | 30.94      | Amazon |

**Total Cost: $63.58**



### Final Thoughts

This project was little difficult than I expected, especially PCB design . I learned a lot about circuit design, CAD modeling, and firmware development. There were many mistakes during the process, but fixing them helped me understand things better. If I do this again, I would plan the design more carefully from the start.

