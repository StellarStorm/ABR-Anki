# Note
```
guid: jR;?PY0D_$
notetype: StuCo/Self Review model
```

### Tags
```
CT
```

## Question
<h2>Advantages of iterative reconstruction over FBP</h2>

## Answer
<section>
<ol>
<li>Can reduce noise during reconstruction by weighting as functions of number of measured photons (“weighted least squares solution”)</li>
<li>Less sensitive to sparse data</li>
<li>Can be applied in image space and raw data space</li>
</ol>
<p>1 and 2 imply: we can reduce the dose needed to get the same quality image </p>
<p>For reference, recall that iterative reconstruction works like this:
- Let \(\vec{x}\) represent the image
- Let \(\boldsymbol{A}\) represent the physics of acquisition (the “forward projection operator”)
- Let \(\vec{b}\) represent the projections</p>
<p>We say \(\boldsymbol{A}\vec{x} = \vec{b}\)
Directly solving for \(\hat{x} = (\boldsymbol{A}^T \boldsymbol{A})^{-1} \boldsymbol{A}^T \vec{b}\) isn’t feasible due to prohibitively large computational cost (TB of memory for a single slice)</p>
<p>Instead we start with an initial guess, compute the forward projection, and then iteratively minimize the difference between the forward projection guess and the measured projection
\(x_{iter} = argmin_{\vec{x}} || \boldsymbol{A}\vec{x} - \vec{b}||\) </p>
<p><img alt="" src="6D080DEC-2ACA-4B99-B74C-B57B17DBD5C0.png"/></p>


</section>

## Guid
jR;?PY0D_$
