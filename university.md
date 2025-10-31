---
layout: page
title: Academic projects
subtitle: Some excerpts of projects achieved during my undergraduate studies.
---

I make available the following personnal notes. It is though licensed under the following Creative Commons licence : <a href="https://creativecommons.org/licenses/by-nc/4.0/">CC BY-NC 4.0</a><img src="https://mirrors.creativecommons.org/presskit/icons/cc.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/by.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/nc.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;">

## Briggs-Rauscher reaction (1st year)

In intensive preparation classes for the "Grandes Écoles" (more commonly called "classes prépa" in France), so my first year of studies, we had a mandatory project called Suppervised Personnal Initiative Projects. We had to design, in one and a half year, a problematic, elements of answer and practical manipulations associated, fitting with national-annual-imposed theme. 2024-2025 theme was "Transitions, Transformations, Conversions". Unfortunately, I had to end my studies in "classe prépa" before I could achieve this project. Here is still the work I did during approximatively four months. Even if the project has never been ended, this is so far my most important one.

I wanted to focus on chemical reactions that were relevant in the context of the theme "Transitions, Transformations, Conversions". This is how I heard about oscillating reactions and discovered the Briggs-Rauscher reaction. After a couple of weeks of research, I tested to protocols and agreed to follow this one :

> Mix 10 mL of each following solutions in a beaker :<br>
> Solution A : hydrogen peroxyde at 4.0 M<br>
> Solution B : potassium iodate at 0.20 M, sulfuric acid at 0.077 M<br>
> Solution C : malonic acid at 0.15 M and potassium permanganate at 0.20 M<br>
> Eventually add a few drops of thionine to color better the two different phases of the reaction. Starch alone was note sufficient in our reactionnal<br> media.
> - Feldwinn, D. P. Briggs–Rauscher Oscillating Reaction. University of California, Santa Barbara, Department of Chemistry and Biochemistry. Retrieved from https://people.chem.ucsb.edu/feldwinn/darby/DemoLibrary/DemoPDFs/Demo005.pdf

I then wanted to have an overview of the oscillator characteristics, especially the period of an oscillation and the duration of the reaction happening. I first thought of using a spectrophotometer, although at those concentrations, hydrogen peroxyde was subject to a lot of dismutation and was thus releasing a lot of dioxygen which was forming huge bubles preventing us from being able to do a decent spectrophotometric monitoring.
So my teacher and I decided to try to make an AgI selective electrode using electrolysis, and surprisingly, the electrolysis never formed but a depot of it formed naturally while letting the electrode soak in a potassium iodate solution. Because of the RedOx reactions happening, the electrical potential E in the solution should have oscillated with the composition of the reactionnal media. Instead, my homemade electrode was not good enough to give me exploitable results. _See in the figure below where I plotted 17 acquisitions of **E = f(t)** for the same solutions used_.

<figure>
  <img
    src="/assets/img/tipe_electrodes.png"
    alt="Graph of E = f(t) using AgI selective homemade electrode for the Briggs-Rauscher reaction"
    width="1200"
    height="600"
    loading="lazy"
    style="max-width:100%;height:auto;display:block;margin:0 auto;"
  />
  <figcaption style="text-align:center;font-size:0.9em;margin-top:0.4em;">
    17 acquisitions of E = f(t) for the Briggs–Rauscher reaction, plotted together. <i>French legend</i>
  </figcaption>
</figure>

So I decided to back to my first idea of spectrophotometry. But instead of doing it in a spectrophotometer, I kind of build my new one. The cuve I used was higher so the bubbles were mostly accumulating at the top. It was also way larger and a bit deeper. I added stirring to help eliminate the dioxygen bubbles faster. I put a laser at a wavelenght were diode was absorbing decently (I used green, the best I could have used was blue). On the other side of the cuve, I put a lux meter protected from the ambiant light by a cupboard roll. I connected the lux meter to the computer and had, here, very satisfactorying oscillations.

<div style="display: flex; justify-content: center; gap: 1rem; flex-wrap: wrap;">
  <figure style="flex: 1; text-align: center; min-width: 250px;">
    <img src="/assets/img/tipe_schema.png"
         alt="Initial schema of what the experimental setup should look like"
         style="max-width: 100%; height: auto; border-radius: 8px;">
    <figcaption style="font-size: 0.9em; color: #555;">Initial schema of what the experimental setup should look like. <i>French text</i></figcaption>
  </figure>

  <figure style="flex: 1; text-align: center; min-width: 250px;">
    <img src="/assets/img/tipe_dispositif.jpg"
         alt="Experimental setup used to visualise the oscillations, with both the lux meter method and the electrodes"
         style="max-width: 100%; height: auto; border-radius: 8px;">
    <figcaption style="font-size: 0.9em; color: #555;">Experimental setup used to visualise the oscillations, with both the lux meter method and the electrodes</figcaption>
  </figure>
</div>


---

## Oscillating reactions (2nd year)

On fourth semester, we had to present, in five minutes, a topic in anything related to our field of studies. So I decided to continue my work about oscillating reactions after my **project on the Briggs-Rauscher reaction** in first year. You will find below the slides used to illustrate my presentation.

I focused on the links between oscillating reactions and physics as well as math to reach the fields of study of all the students in the group. I introduced the most common oscillating reactions to the audience (Bray–Liebhafsky, Briggs-Rauscher, Belousov-Zhabotinsky) as well as some uncommon ones (oscillations of candle flames' height). I then proposed a funny and visual application of the oscillating reactions with the Traffic Light experiment and how we can use it to build a timer.

<iframe
  src="/assets/files/Oscillations diaporama.pdf"
  width="100%"
  height="500px"
  style="border: none;"
>
</iframe>
