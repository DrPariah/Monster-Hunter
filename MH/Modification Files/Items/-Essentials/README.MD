## Material Data
Material strength are based mainly on MHFU's low rank armor of a monster material, while some exclusive armors beyond high rank and G are diminished greatly in this formulation:

* High rank = `defense` * 0.60
* G rank = `defense` * 0.5

The results are forwarded to resistance and weapon damage calculations.

### Resistance
* **bash** = `defense` / 4 * 1.25
* **cut** = `defense` / 3 * 1.25
* **acid** = `water` + `ice` / 2 * 3
* **fire** = `fire` * 1.75
* **elec** = `thunder` * 1.75
* **chip** = 12

### Weapon Damage
* ***base*** = **bash** + **cut** / 2 * 2.5

***Base*** is required to calculate the damage by weapon type.