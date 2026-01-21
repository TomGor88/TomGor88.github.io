---
layout: post
title: 'Design, Fabrication, and Testing of a Needle-Sized Wrist for Surgical Instruments'
---

Minimally invasive surgery is constantly being redefined by surgeons and engineers as surgical devices continue to decrease in
size. However, it becomes increasingly more difficult to create dexterous surgical instruments. Consequently, existing needle-sized devices have limited dexterity and provide a limited number of degrees-of-freedom, reducing their potential impact.\
The goal of this project focuses on providing additional degree-of-freedom and dexterity to needle-sized surgical tools.
I have created a surgical end-effector for an endoscopic submucosal dissection procedure. The wrist is made using asymmetric, rectangular cutouts in a nitinol tube, forming a compliant bending region that is actuated with a tendon. This design endows the ability to navigate around sharp corners to manipulate and visualize tissue.
<video width="608" height="300" style="text-align: center" controls>
  <source src="{{ site.github.url }}/assets/img/projects/proj-a/HelpingHandDemo.mp4" type="video/mp4">
</video>
The wrist is capable of achieving 2 DoF in a single bending plane to achieve the desired S-shaped curves. 
{% include image2.html image="projects/proj-a/IMG_03.png" %}
Perhaps counter-intuitively, within this seemingly simple design concept, design optimization is challenging due to the number of parameters available and nonlinearities in material properties.
{% include image2.html image="projects/proj-a/WristCNC.jpg" %}
Nitinol is a shape memory alloy (SMA) composed of nickel and titanium, with unique properties, including superelasticity and shape memory in its austenitic state. Its flexibility and elasticity allow the wrist to snap back to its original shape when stress is released. 
These properties also make it extremely difficult to manufacture using the CNC-mill. I utilized a series of miniature-size endmills, the smallest one with a diameter of 0.5mm diameter. These small endmills are extremely brittle and require perfect feed & speed to cut and not break itself.
