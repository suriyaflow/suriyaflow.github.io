---
permalink: /
title: # "suriya's academic website"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Table with Hover Descriptions</title>
    <style>
        table {
            width: 100%;
            table-layout: fixed;
        }

        td {
            text-align: center;
            padding: 10px;
        }

        .image-container {
            display: inline-block;
            position: relative;
            vertical-align: top; /* Aligns images correctly in the table cell */
        }

        .description {
            visibility: hidden; /* Initially hidden */
            opacity: 0;
            transition: opacity 0.5s, visibility 0s linear 0.5s; /* Add visibility to the transition */
            background-color: rgba(0, 0, 0, 0.7);
            color: white;
            padding: 5px;
            margin-top: 5px;
            border-radius: 5px;
            height: 0; /* Initial height */
            overflow: hidden;
            transition: height 0.5s ease, opacity 0.5s ease; /* Smooth transition for height and opacity */
        }

        .image-container:hover .description {
            visibility: visible; /* Make visible when hovered */
            opacity: 1;
            height: auto; /* Auto height to fit content */
            transition-delay: 0s; /* Transition delay for smooth effect */
        }

        img {
            max-width: 100%;
            height: auto;
        }
    </style>
</head>


👋 Hello, I am Suriya, a final-year Ph.D. candidate at TU Delft in the Netherlands. 🔬 I am interested in instabilites, self-assembly and pattern formation driven by physicochemical hydrodynamics. 


<div style="display: flex; align-items: center;">
 <!-- <a href = ""> -->
<img src="./images/evaporation_driven_buckling_sch.png" alt="Alt Text" align="right" width="300" style="margin-right: 30px;">
 <!-- </a> -->
<p style="text-align: justify;"> 🎓🎓🎓 In my Ph.D. thesis I focus on evaporation of particle-laden drops and the buckling of such drops. I am supervised by <a href="https://www.tudelft.nl/staff/l.botto/?cHash=7ba1f9f844091f98d5670993cb9cc996">Dr. Lorenzo Botto</a>  in the <a href = "https://www.tudelft.nl/me/over/afdelingen/process-energy/research/complex-fluid-processing">Complex Fluids Processing Group</a> at TU Delft. I try to work on projects that have an impact on climate change. I am also passionate about open science & hardware. Here are some <a href="https://suriyaflow.github.io/suriyaprakash.github.io/opensource/">open source projects</a> that I have developed. </p>
</div>


<div style="display: flex; align-items: center;">
  <img src="./images/spiralling_liq_jet.png" alt="Alt Text" width="300" align="right" style="margin-right: 30px;">
  <p style="text-align: justify;">🎓🎓 I did my master in Energy, flow and process technology also from TU Delft. For my thesis I built an experimental setup that resembles the prilling process which is used to make fertilizers under the supervision of Dr. Wim Paul Breugem and Dr. Burak Eral. I was able to control the process parameters in spinning jet breakup to reduce the production of satellite drops (dust particles) in prilling. It is estimated that each prilling tower emits 1500 tons of nitrogen based pollutants in to the air every year. I was able to successfully eliminate the satellite drops in the model prilling machine I built. Read my <a href = "http://resolver.tudelft.nl/uuid:2d4a4fec-0637-4fa4-842e-f6e924cf8369">thesis</a> or our <a href = "https://www.cambridge.org/core/journals/journal-of-fluid-mechanics/article/controlling-the-breakup-of-spiralling-jets-results-from-experiments-nonlinear-simulations-and-linear-stability-analysis/06D64EB348A30FFE210F42BE8192E4DF">paper.</a></p>
</div>

<table>
        <tr>
            <td>
                <div class="image-container">
                    <img src="image1.jpg" alt="Description of Image 1">
                    <div class="description">Description for image 1.</div>
                </div>
            </td>
            <td>
                <div class="image-container">
                    <img src="image2.jpg" alt="Description of Image 2">
                    <div class="description">Description for image 2.</div>
                </div>
            </td>
            <td>
                <div class="image-container">
                    <img src="image3.jpg" alt="Description of Image 3">
                    <div class="description">Description for image 3.</div>
                </div>
            </td>
        </tr>
        <tr>
            <td>
                <div class="image-container">
                    <img src="image4.jpg" alt="Description of Image 4">
                    <div class="description">Description for image 4.</div>
                </div>
            </td>
            <td>
                <div class="image-container">
                    <img src="image5.jpg" alt="Description of Image 5">
                    <div class="description">Description for image 5.</div>
                </div>
            </td>
            <td>
                <div class="image-container">
                    <img src="image6.jpg" alt="Description of Image 6">
                    <div class="description">Description for image 6.</div>
                </div>
            </td>
        </tr>
    </table>
