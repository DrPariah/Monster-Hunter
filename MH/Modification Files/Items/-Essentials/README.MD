## Material Data
Material strength are based mainly on MHFU's low rank armor of a monster material, while some exclusive armors beyond high rank and G are diminished greatly in this formulation:

* High rank = `defense` * 0.7
* G rank = `defense` * 0.6

The results are forwarded to resistance and weapon damage calculations.

### Resistance
* **bash** = `defense` / 4 * 1.25 + 10
* **cut** = `defense` / 3 * 1.25 + 10
* **acid** = `water` + `ice` / 2 * 3
* **fire** = `fire` * 1.75
* **elec** = `thunder` * 1.75
* **chip** = 12

### Weapon Damage
This is calculated before adding the 10 to **bash** and **cut** resistance results.

* ***base*** = **bash** + **cut** / 2 * 2.5

***Base*** is required to calculate the damage by weapon type.