# A7 – [Topic]

## Set Up

<img width="1173" height="946" alt="Screenshot 2026-10-20 213854" src="https://github.com/user-attachments/assets/b46a8e7a-93b6-468a-8aeb-5617b081f23f" />

Prior to starting the assignment, I needed to set up the simulation. I first started by finding some part of the object to fix and resist the force that would be experienced on the cylinder at the bottom of this part. I fixed the inner top surface of the part to resist the force experienced to run this simulation.

<img width="778" height="953" alt="Screenshot 2026-10-20 215257" src="https://github.com/user-attachments/assets/1c1aa7f8-02a3-4115-a562-b0cea8bd41dc" />

I next added the force to the simulation, ensuring it all headed in the correct direction and had a magnitude of 650 lbf, as utilized in my previous calculation for this part design.

## Test (Original Design)

After setting up my part to conduct the FEA, I then ran three different tests on different mesh densities. These being coarse, medium, and fine. After fully condusting this test and seeing if their values fell witin 7% of one another that was not the result so I then proceeded to the next step, design optimation. 

### Test 1
| | (Coarse) |  (Mid) | (Fine)|
|---|---|---|---|
|  Max Stress and Location | 1.329e+09 N/m^2 | 1.684e+09 N/m^2 | 1.139e+08 N/m^2 |
|  | <img width="800" height="500" alt="image" src="https://github.com/user-attachments/assets/27ee7738-120e-4436-8f27-d91d08948861" /> | <img width="800" height="500" alt="image" src="https://github.com/user-attachments/assets/0f2b0344-9b57-4809-a660-56af33b38882" /> | <img width="1524" height="1113" alt="Screenshot 2026-10-20 235835" src="https://github.com/user-attachments/assets/73a78bd5-6ff3-468e-b44b-553cafda08bc" /> |
|  Max Deflection and Location | 2.849e+01 mm | 3.039e+01 mm | 3.082e-01 mm |
|  | <img width="1476" height="1014" alt="image" src="https://github.com/user-attachments/assets/3fd7f2a9-c1b5-4000-905b-567b4c04125f" /> | <img width="1510" height="1049" alt="image" src="https://github.com/user-attachments/assets/322a3654-bd45-4f79-bc0d-45812ef519a3" /> | <img width="1458" height="1068" alt="Screenshot 2026-10-21 000418" src="https://github.com/user-attachments/assets/47bb669b-50bc-4b1f-bd5e-920184c1d01f" /> |
| Mass |  .99 lb | .99 lb | .99 lb |
| Safety Factor | .2068 | 0.1633 | .1504 |
| Number of Elements | 1267 | 8539 | 62317 |

## Decide

<img width="548" height="572" alt="image" src="https://github.com/user-attachments/assets/65bb9fbf-51f8-4516-9d76-5401720711cd" />

Consern 

<img width="712" height="893" alt="image" src="https://github.com/user-attachments/assets/e4e36687-6981-4b50-b050-d6872afd2ca0" />

### Design alteration

| | Design 1 (Coarse) | Design 2 (Mid) | Design 3 (Fine)|
|---|---|---|---|
|  Max Stress and Location | 4.751e+07 N/m^2 | 7.497e+07 N/m^2 | 1.139e+08 N/m^2 |
|  | <img width="1687" height="978" alt="image" src="https://github.com/user-attachments/assets/5bebb24b-52a4-4f1e-8697-2219090f8bd7" /> | <img width="1653" height="990" alt="image" src="https://github.com/user-attachments/assets/f7310f8c-86e3-4910-86cd-6587592d5f9a" /> | <img width="1798" height="1060" alt="image" src="https://github.com/user-attachments/assets/e9a0309a-eeaf-4288-8b87-d41b97ef9e66" /> |
|  Max Deflection and Location | 6.546e-02 mm | 7.124e-02 mm | 7.222e-02 mm |
|  | <img width="1682" height="965" alt="image" src="https://github.com/user-attachments/assets/0eff5c6d-4aa2-4b71-9d09-daf07a24932b" /> | <img width="1526" height="943" alt="image" src="https://github.com/user-attachments/assets/0e19546b-84d8-43a9-891b-9dd79f506d7b" /> | <img width="1556" height="968" alt="image" src="https://github.com/user-attachments/assets/c63ae2b7-4e4f-4fa2-87b3-409731a99aad" /> |
| Mass |  .81 lb | .81 lb | .81 lb |
| Safety Factor | 5.789 | 3.668 | 2.414 |
| Number of Elements | 1409 | 8877 | 63605 |

## Communicate

<img width="424" height="433" alt="image" src="https://github.com/user-attachments/assets/fbe8a357-9dcb-447d-abcc-3d95523992bb" />

Consern

Change 

<img width="1128" height="1000" alt="image" src="https://github.com/user-attachments/assets/c2f806e9-fad5-453d-982d-9b30d61e7791" />

<img width="667" height="811" alt="image" src="https://github.com/user-attachments/assets/6c62a4a8-7654-4895-87b3-1a5671e68651" />

## Chart

| | Design 1 (Coarse) | Design 2 (Mid) | Design 3 (Fine)|
|---|---|---|---|
|  Max Stress and Location | 9.739e+07 N/m^2 | 1.203e+08 N/m^2 | 1.259e+08 N/m^2 |
|  | <img width="871" height="470" alt="image" src="https://github.com/user-attachments/assets/98ab6bfc-1fac-405e-b1f7-b2464bbec71d" /> | <img width="869" height="470" alt="image" src="https://github.com/user-attachments/assets/a920c0b9-f8fd-49b0-881c-a5631ec5db68" /> | <img width="1797" height="1018" alt="image" src="https://github.com/user-attachments/assets/992d4167-e900-4ebf-b2bd-4ec343db9f1f" /> |
|  Max Deflection and Location | 5.336e-02 mm | 5.557e-02 mm | 5.664e-02 mm |
|  | <img width="827" height="477" alt="image" src="https://github.com/user-attachments/assets/02834a28-b654-403b-b307-1a4ed2926207" /> | <img width="832" height="477" alt="image" src="https://github.com/user-attachments/assets/164fd540-15f7-4b3c-92f2-e390b0af354f" /> | <img width="1782" height="996" alt="image" src="https://github.com/user-attachments/assets/6822b8ba-4f6f-48f7-9dd2-55d42431810d" /> |
| Mass |  .89 lb | .89 lb | .89 lb |
| Safety Factor | 2.824 | 2.286 | 2.185 |
| Number of Elements | 2332 | 10761 | 66579 |



