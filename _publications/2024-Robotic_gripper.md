---
title: "Learning to estimate incipient slip with tactile sensing to gently grasp objects"
collection: publications
category: conferences
permalink: /publication/2010-10-01-paper-title-number-2
excerpt: 'This paper is about a new algorithm to control delicate robotic gripper based on the safety margin.'
image: '/images/robotic_grasping.png'
date: 2024-05-07
venue: 'ICRA'
slidesurl: #'http://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://drive.google.com/file/d/1yJgend6CE8i2glRA4FMG3KdEnQLtNe5L/view'
citation: #'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---

**Abstract** To gently grasp objects, robots need to balance generating enough friction yet avoiding too much force that could damage the object. In practice, the force regulation is challenging to implement since it requires knowledge of the friction coefficient, which can vary from object to object and even from grasp to grasp. Tactile sensing offers a window in the contact mechanics and provides information about friction. Notably touch can detect the precursor of the object slipping away from the grasp. To find this information, tactile sensors measure the deformation field of an artificial skin in both the normal and tangential direction. However, current approaches only react to slip and therefore react too late to perturbations. The object slips, inducing a failure of the grasp and damage. In this study, we introduce a method that uses machine-learning to anticipate slip by computing the so-called safety margin of the grasp. This safety margin represents the extra lateral force that maintains the contact away from the frictional limit. To find this value, we use a high-density camera-based tactile sensor to measure the 3D deformation of the surface via the movement of 82 colored markers. We trained a Convolutional Neural Network (CNN) to estimate the safety margin from the tactile images. Because it gives a distance to slip, the safety margin is a powerful metric for regulating grasp forces. As a testament of this effectiveness, we show that a simple proportional controller can robustly grasp a wide variety of objects. The results show that this control method outperforms slip detection methods, by reducing regrasp reaction times while decreasing grasping forces to 1-3 N.
