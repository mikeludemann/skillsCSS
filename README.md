# Skills CSS

Simple CSS formats for skills

## Examples

```code

Normal and border skill bars

<div class="container">
    <div class="skills wh-100-50">100%</div>
</div>

<div class="container radius-5">
    <div class="skills wh-45-50 radius-5">45%</div>
</div>

<div class="container radius-25">
    <div class="skills wh-60-50 radius-25">60%</div>
</div>

Rounded skill bars

<div class="pie-wrapper progress-50">
    <span class="label">50<span class="smaller">%</span></span>
    <div class="pie">
        <div class="left-side half-circle"></div>
        <div class="right-side half-circle"></div>
    </div>
</div>

<div class="pie-wrapper progress-25 without">
    <span class="label">25<span class="smaller">%</span></span>
    <div class="pie">
        <div class="left-side half-circle"></div>
        <div class="right-side half-circle"></div>
    </div>
    <div class="shadow"></div>
</div>

<div class="pie-wrapper pie-wrapper--solid progress-35">
    <span class="label">35<span class="smaller">%</span></span>
</div>

```