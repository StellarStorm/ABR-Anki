# Note
```
guid: f6It6ecy+7
notetype: Ford Primer on RO Physics model
```

### Tags
```
Brachytherapy
Ford
Therapy
```

## Question
<h2>Describe the calculation of brachy dose rate</h2>

## Answer
<section>
<p>\(\dot{D} = S_k \times \Lambda \times G \times g \times F\)
where</p>
<ul>
<li>\(S_k = \dot{X} (\frac{W}{e}) = \dot{X} \times 0.876 cGy/R\) is the <strong>air kerma strength</strong></li>
<li>\(\Lambda\) is the <strong>dose rate constant</strong>, calculated for each source</li>
<li>\(G\) is the <strong>geometry factor</strong> to account for how the true geometry of the source contributes dose at each point</li>
<li>\(G(r, \theta) \approx \frac{1}{r^2}\) for a point source</li>
<li>\(G(r, \theta) \approx \frac{\beta}{L r \sin{\theta}}\) for a line source</li>
<li>\(g\) is the <strong>radial dose function</strong> that accounts for absorption and scatter in the medium</li>
<li>\(F\) is the <strong>anisotropy factor</strong> as there will be self-filtration of the source & the dose will not be evenly distributed.</li>
</ul>
<p><img alt="" src="4215912A-511E-4BFC-AA7F-CB62A1FDD739.png"></p>


</section>

## Guid
f6It6ecy+7
