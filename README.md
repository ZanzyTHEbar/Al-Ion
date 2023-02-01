# Al-Ion
Open Source Project dedicated to rechargable Al-Ion chemistry


Below is the Al Ion Cell Forumla

---

## Reaction Chemistry

Deposition and Dissolution based chemistry.

Capacitive relationship between types of carbon & structures used.

- pseudocapacitance
- redox reaction additives to increase charge density

### `Electrolyte`

`AlCl + Urea + Ethylene Glycol + imidozolium chloride`

- Fumed Silica
  - Ball Milled with `AlCl` to increase surface area and sieved at >=45µm
  - 5-10% by weight of the gel
- DES base
  - ionic liquid
  - 90-95% by weight of the gel
  - AlCl HexaHydrate
  - Ethylene Glycol
  - Urea
    - 1-5% by weight of the of the DES base
  - Imidozolium Chloride
    - 70-85% by weight of the of the DES base
  - LiCl
    - 0.1-1% by weight of the of the DES base (only on the positive electrode)
    - Increases ionic conductivity of the gel
  - Left over: 5% by weight of the DES base
    - possible additions to lower viscosity
      - Ethylene Carbonate
      - Polymeric Binder

#### `Gel`

There is a gel that is used as the electrolyte, which is made from:

- AlCl + Urea + Ethylene Glycol + imidozolium chloride
- Fumed Silica Nano-particles
- Emulsified in Deep Eutectic Solvent (DES) ionic liquid
- (optional) 1% by weight of a polymeric binder
- (optional) 1% by weight of eythylene carbonate to decrease viscosity

This gel is then cast into a thin film of aprox `4mm`.

One gel layer is used for the positive electrode, and one for the negative electrode.

##### `Positive Electrode Gel`

Additon of `0.1%` - `1%` by weight `LiCl` to the gel to increase the ionic-conductivity of the gel (additional charge transport).

### `Separator`

Mesoporous membrane with ion exchange capacity and hydrophobic pores

- Cellulose Acetate
- Fumed Silica Nano-particles
- Ethylene Glycol
- Acetone (to dissolve cellulose acetate)

Mix well and then cast into a thin film.

Once dry, the film is rinsed with water to remove the gylcol and residual acetone.

> **Note**: The film is then placed in a vacuum oven at 80C for 12 hours.
>
> **Note**: The film is soaked in a solution aqueus Cl ion solution for 24 hours, to increase the ion exchange capacity of the membrane.

### `(-) Electrode`

The negative electrode is made from a `graphene` 3D foam by exfoliating Graphene Oxide (GO) using UV light.

The GO is made by a modified Hummers method, with the addition of `carboxymethylaceytlene` (CMC) complexed with Ag to the GO, to increase the conductivity of the resulting graphene after exfoliation.
This material is then mixed with a `polymer binder` to form a paste and coated onto a `10µm<` sheet of `Al` metal.

### `(+) Electrode`

The positive electrode is made from a `graphene` 3D foam by exfoliating Graphene Oxide (GO) using UV light.

The GO is made by a modified Hummers method, with the addition of `carboxymethylaceytlene` (CMC) complexed with Ag to the GO, to increase the conductivity of the resulting graphene after exfoliation.

After exfoliation, the graphene foam is made into an ink by mixing with a `polymer binder` and a `carbon black` to form a paste.

A Nickel Foam is then soaked in this material to form a `Ni foam` coated with `graphene`.

The `Ni Foam` is then freeze-dried to remove the solvent and heated to remove bound `O2`.

## Notes

Potential hydridization by comibining `Ni-Fe` cells with the `Al-Ion` cells.

Could potentially be used as a `Ni-Fe` cell with a `Al-Ion` cell as a `supercapacitor` to increase the charge density.

- 2V @600mA
