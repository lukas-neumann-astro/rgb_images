This repository contains a few scripts (jupyter notebooks), which produce RGB images from HST, JWST and mixed-telescope observations.

We choose the nearby spiral galaxy NGC 4321 as our test example to produce a suite of RGB images across the electromagnetic spectrum from optical over infrared to radio wavelengths.

### 1. HST RGB image

* red = `F814W`
* green = `F555W`
* blue = `F438W`

### 2. JWST RGB image

* red = `F770W` + `F1000W` + `F1130W` + `F2100W`
* green = `F360M` + `F770W`
* blue = `F300M` + `F335M`

### 3. MUSE-JWST-ALMA composite image

* red = `H-alpha` ionised gas emission (MUSE)
* green = `F770W` polycyclic aromatic hydrocarbon (PAH) dust emission (JWST)
* blue = `CO(2-1)` molecular line emission (ALMA)
