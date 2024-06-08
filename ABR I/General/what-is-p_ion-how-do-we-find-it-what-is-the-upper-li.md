# Note
```
guid: zyq?[LFaUg
notetype: TG51 model
```

### Tags
```
TG-51
```

## Question
<h2>What is \(P_{ion}\)? How do we find it? What is the upper limit for use?</h2>

## Answer
<section>
<p>\(P_{ion}\) is the recombination factor which corrects for the fact that some ion pairs will recombine before their charge can be corrected. We find it by measuring ion chamber ourput at two different voltages (-300V and -150V typically). Then, for continuous beams, the formula is</p>
<p>\(P_{ion} = \frac{1 - (V_H/V_L)^2} {M_H/M_L - (V_H/V_L)^2}\)</p>
<p>and for linac beams (probably what we’re doing), the formula is</p>
<p>\(P_{ion} = \frac{1 - V_H/V_L} {M_H/M_L - V_H/V_L}\)</p>
<p>\(P_{ion}\) must be less than 1.05 or the uncertainty is too great and a different ion chamber must be used.</p>
<p>Note that \(P_{ion}\) is a function of dose <u>​per pulse</u>. This is why there are two forms, one for a continuous beam and one for a pulsed linac beam.</p>

</section>

## Guid
zyq?[LFaUg
