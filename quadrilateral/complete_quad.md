---
title: Properties of Complete Quadrilaterals
description: 
published: true
date: 2022-06-11T08:22:23.053Z
tags: 
editor: markdown
dateCreated: 2022-06-11T02:07:16.794Z
---

# Properties of Complete Quadrilaterals
Let $\mathcal Q=ABCDEF$ be a complete quadrilateral such that $E=AB\cap CD$, $F=BC\cap DA$, $B$ on segment $AE$ and $D$ on segment $AF$.

## Shared Properties
- The midpoints of three diagonals $AC$, $BD$ and $EF$ are collinear; the line is called the *Newton line*, and will be denoted by $m_\mathcal Q$.
- The orthocenters of *the four triangles* $AED$, $AFB$, $BEC$, $DFC$ are collinear; the line is called the *Gauss-Bodenmiller line*, and will be denoted by $h_\mathcal Q$.
  - $h_\mathcal Q\perp m_\mathcal Q$.
- The circumcircle of the four triangles are concurrent; the point is called the *Miquel point*.
- Suppose $X$ is a point such that $\angle EXB=\angle FXD$, then $\angle BXC=\angle DXA$.

## Special Properties

### Foot-Circular Complete Quadrilaterals
If $BEFD$ is circular, call this complete quadrilateral *foot-circular*.

For foot-circular complete quadrilateral $ABCDEF$ with $\Omega=\odot BEFD$:

- The pole of $BD$ w.r.t. $\Omega$ and the pole of $EF$ w.r.t. $\Omega$ both fall on $AC$.

### Head-Circular Complete Quadrilaterals
If $ABCD$ is circular, call this complete quadrilateral *head-circular*.

For head-circular complete quadrilateral $ABCDEF$ with $\omega=\odot ABCD$:

- Suppose $M$ is the midpoint of $AC$, $N$ is the midpoint of $BD$ and $L$ is the midpoint of $EF$. Then
  - $\displaystyle{\frac{BD}{AC}=\frac{NE}{NM}=\frac{NL}{NE}}$
  - $\displaystyle{\frac{AC}{BD}-\frac{BD}{AC}=\frac{2ML}{EF}}$
  - $\odot AML$, $\odot FCE$, $\omega$ and $AN$ are concurrent.

### In- and Excircles
If $\triangle AEC$ and $\triangle AFB$ has an common incircle, we say this circle is an *incircle* of $\mathcal Q$.

- For any three points $\{X,Y,Z\}\subset\{A,B,C,D,E,F\}$, if $\triangle XYZ$ is not $\triangle AED$, $\triangle AFB$, $\triangle BEC$ or $\triangle DFC$ (i.e. not a triangle of the original $\mathcal Q$), then $\mathcal Q$ has an incircle $\iff$ the angle bisector of $\angle X$, $\angle Y$ and $\angle Z$ are concurrent.
- $\star$ $\mathcal Q$ has an incircle $\iff AB+CD=BC+DA\iff BE+BF=DE+DF\iff AE+CF=AF+CE$.

If $\triangle AEC$ and $\triangle AFB$ has an common $A$-excircle, we say this circle is an *excircle* of $\mathcal Q$.

- $\mathcal Q$ has an excircle $\iff AB+BC=CD+DA\iff AE+EC=AF+FC\iff BE+ED=BF+FD$.
