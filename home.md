---
title: Welcome!
description: Welcome page / Home page
published: true
date: 2022-06-11T06:44:18.897Z
tags: 
editor: markdown
dateCreated: 2022-06-08T07:40:55.328Z
---

# Welcome!
GeoWiki is a wiki for geometrical properties, especially triangle properties. There are some conventions in this wiki.

## Conventions
Points defined are meant to be *symmetrical*, i.e. If a point is defined for $A$, it should also be defined for $B$ in a same manner. Therefore we write points in the form of $X_A$, meaning the definition of point $X$ with respect to $A$. For example:

> $M_A$ is the midpoint of edge $BC$.

Then we assume $M_B$ is the midpoint of edge $AC$, $M_C$ is the midpoint of edge $BC$. Lines are similar;

> $m_A$ is the median of $A$.

Then $m_B$, $m_C$ are also defined. A list of namings can be found [here](/naming/triangle_list). Notice that every point that doesn't appear in this list (e.g. $X_A$, $Y_A$, $Z_A$. These 3 names are actually reserved) is default to the local definition.

Also notice that, if we consider multiple triangles at one time, a subscript that indicates the triangle will be added: so $m_A=m_{\triangle ABC,A}$ and $P=O_{\mathcal J}$. If no subscript is present it is default to $\triangle\mathcal A=\triangle ABC$. For a list of triangles also see the name list.

### Fonts
Usually all objects will be named in `\mathnormal` font; for objects with name more than 1 letters, upright font `\mathrm` will be used for points and circles, `\mathfrak` will be used for lines; values are always in `\mathbf`; triangles are always in `\mathcal`.
