---
layout: post
title: "What Frame Are We in"
date: 2012-10-29 09:58
comments: true
categories: 
toc: true
---

Synge once said, use space and time, and define them.

This post is aimed to make clear what frame are we in. 

<!-- more -->

## Intro

In general relativity, we often transform coordinates. Here is an example.

**The general form of metric with spherical space component is**

\begin{equation} \mathrm ds^2 = - \gamma(r,t)c^2\mathrm dt^2 + \beta(r,t)c\mathrm dr\mathrm dt + \alpha(r,t)[\mathrm dr^2 + r^2 (\mathrm d\theta^2 + \sin^2\theta \mathrm d\phi^2)]\label{MetricForm1} \end{equation}

With a transformation $\alpha(r,t)r^2 = r'^2$, 

$$\mathrm ds^2 = - \gamma'(r',t)c^2\mathrm dt^2 + \beta'(r',t)c\mathrm dr\mathrm dt + \alpha(r,t)[\mathrm dr^2 + r^2 (\mathrm d\theta^2 + \sin^2\theta \mathrm d\phi^2)] $$


Then compose the integral multiplier

$$c\mathrm dt'= \eta(r',t) [ - \gamma'(r',t) c \mathrm dt + \frac{1}{2} \beta'(r',t)\mathrm dr'] $$

And finally,

$$\mathrm ds^2 = -\eta^{-2}(r',t) \gamma'^{-1}(r',t)c^2\mathrm dt'^2 + [\alpha'(r',t) + \frac{\beta'^2(r',t)}{4r'} ]\mathrm dr'^2 + r'^2(\mathrm d\theta^2 + \sin^2\theta\mathrm d\phi^2) $$

In general

\begin{equation}
\mathrm ds^2 = -b(r,t)c^2\mathrm dt^2 + a(r,t)\mathrm dr^2 + r^2(\mathrm d\theta^2 + \sin^2\theta\mathrm d\phi^2) \label{MetricForm2}
\end{equation}

Then what? The two forms of metric demonstrate different properties. Take Birkhoff theorem as an example. The results could be very different startting from the form (\ref{MetricForm1}) and (\ref{MetricForm2}).

It is obviously very important to show what the coordinate transformation means and what frame are the observers in indicated by the coordinates.



## Frame and Coordinates










