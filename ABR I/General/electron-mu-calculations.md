# Note
```
guid: EEY:]n{p{X
notetype: Basic
```

### Tags
```
Physics
Therapy::Electrons
```

## Front
Electron MU calculations

## Back
\[MU = \frac{Rx}{K \times PDD \times AF \times CF \times TT \times ISC}\]where
<ul><li>MU is the number of monitor units to be delivered</li><li>Rx is the prescription dose at the depth of interest (cGy)</li><li>K is the calibration output factor (cGy/MU)</li><ul><li>Typically 1cGy/MU at d<sub>max</sub> in a 10x10cm field and SSD of 100cm</li></ul><li>PDD is percent depth dose</li><li>AF is the applicator factor (relates output with specified applicator to output with reference applicator which is typically 10x10cm) \(AF = \frac{\text{Output with applicator}}{\text{Output with reference applicator}}\)</li><li>CF is the cutout factor (relates output with the cutout in the applicator the the output without the cutout) \(CF = \frac{\text{Output with cutout}}{\text{Output without cutout}}\)</li><li>TT is treat to level, assumed to be 1 if isodose line is not specified (e.g., if prescribing to the 90% isodose line, TT=0.9).</li><li>ISC is the inverse square correction, \(ISC = (\frac{VSD + d_{max}}{VSD + g + d_{max}})^2 \)</li><ul><li>VSD is the virtual source distance</li><li>g is the difference between the reference SSD and the setup SSD</li></ul></ul>

## Reference
<a href="https://oncologymedicalphysics.com/dose-calculation-hand-methods/">https://oncologymedicalphysics.com/dose-calculation-hand-methods/</a>
