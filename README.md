# gas_calculator



## Equations of state

| Equation | Year | Parameters needed |
|---|---|---|
| Ideal gas | — | — |
| van der Waals | 1873 | Tc, Pc |
| Redlich-Kwong (RK) | 1949 | Tc, Pc |
| Soave-Redlich-Kwong (SRK) | 1972 | Tc, Pc, ω |
| Peng-Robinson (PR) | 1976 | Tc, Pc, ω |

All four real-gas equations share the same form:

P = RT/(Vm − b) − (attraction term)

The repulsion term is identical; they differ only in the attraction term.
SRK and PR add a temperature-dependent α(T) based on the acentric factor ω,
which is why they predict vapor pressures better than vdW and RK.

## Features

(무엇을 할 수 있는지 3~4개)

## Usage

Example:

```
[CO2] Enter three values > 0.5 L, 1 mol, 300 K

  Solving for P

  Ideal       49.2360 atm    (gas, Ambrose-Walton)
  vdW         39.4211 atm    (gas, Ambrose-Walton)
  RK          38.4481 atm    (gas, Ambrose-Walton)
  SRK         38.3861 atm    (gas, Ambrose-Walton)
  PR          37.7033 atm    (gas, Ambrose-Walton)
```

## Plots
(이미지 — 각각 위에 한 줄 설명)

<img width="567" height="455" alt="H2O at 480 Z per P" src="https://github.com/user-attachments/assets/5e4e7524-ce32-4c58-8ae7-8cc70c3ef6c0" />


<img width="567" height="455" alt="CO2 in PR Z per P in several T" src="https://github.com/user-attachments/assets/3a8ab26c-96d2-475d-a5a3-e9b0bc3c2677" />


<img width="571" height="459" alt="CO2 P-V isotherms(RK) in several T" src="https://github.com/user-attachments/assets/a7e0b29b-55ba-40b4-9ddc-abf48eb10a97" />


<img width="567" height="455" alt="Generalized compressibility chart(PR) several Material" src="https://github.com/user-attachments/assets/4ff6a4e4-498c-437e-8b1e-719516b94a88" />


<img width="563" height="455" alt="CH4 deviation from ideal gas (PR) P-T" src="https://github.com/user-attachments/assets/f45e4659-5ead-4104-b048-ca9bc25d5f48" />
















