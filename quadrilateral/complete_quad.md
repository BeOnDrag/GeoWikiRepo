---
title: Properties of Complete Quadrilaterals
description: 
published: true
date: 2022-06-12T06:21:05.969Z
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

### Foot-Concyclic Complete Quadrilaterals
If $BEFD$ is concyclic, call this complete quadrilateral *foot-concyclic*.

For foot-concyclic complete quadrilateral $ABCDEF$ with $\Omega=\odot BEFD$, $O$ the center of $\Omega$ and $K$ the Miquel point of $\mathcal Q$:

- The pole of $BD$ and the pole of $EF$ w.r.t. $\Omega$ both fall on $AC$.
- $\star$ $BDOK$ is concyclic.
- $KC$ bisects $\angle BKD$ and $\angle EKF$.
- $\star$ $A$, $C$, $K$ are collinear; $\angle OKC=90^\circ$.
- $AC^2=AB\cdot AE+AD\cdot AF$.

### $\star$ Head-Concyclic Complete Quadrilaterals
If $ABCD$ is concyclic, call this complete quadrilateral *head-concyclic*.

For head-concyclic complete quadrilateral $\mathcal Q=ABCDEF$ with $\omega=\odot ABCD$ and $AC\cap BD=P$:

- The pole of $BD$ and the pole of $AC$ w.r.t. $\omega$ both fall on $AC$.

Suppose $O$ is the center of $\omega$.
- The pole of $P$ w.r.t. $\omega$ is $EF$; the pole of $E$ w.r.t. $\omega$ is $FP$; the pole of $F$ w.r.t. $\omega$ is $EP$.
- $O$ is the orthocenter of $\triangle EFP$.
- The projection of $O$ on $EF$ is the Miquel point $K$ of $\mathcal Q$.
- $\star$ $AOCK$ is concyclic; $BODK$ is concyclic.

Suppose $M$ is the midpoint of $AC$, $N$ is the midpoint of $BD$ and $L$ is the midpoint of $EF$. Then
- $\displaystyle{\frac{BD}{AC}=\frac{LE}{LM}=\frac{LN}{LE}}$
- $\displaystyle{\frac{AC}{BD}-\frac{BD}{AC}=\frac{2MN}{EF}}$
- $\odot AMN$, $\odot FCE$, $\omega$ and $AL$ are concurrent.
- $EF\cap BD$, $EF\cap AC$, $M$ and $N$ are concyclic.
- The power of $L$ w.r.t. $\omega$ equals to $LE^2$.

### In- and Excircles
If $\triangle AEC$ and $\triangle AFB$ has an common incircle, we say this circle is an *incircle* of $\mathcal Q$.

- For any three points $\{X,Y,Z\}\subset\{A,B,C,D,E,F\}$, if $\triangle XYZ$ is not $\triangle AED$, $\triangle AFB$, $\triangle BEC$ or $\triangle DFC$ (i.e. not a triangle of the original $\mathcal Q$), then $\mathcal Q$ has an incircle $\iff$ the angle bisector of $\angle X$, $\angle Y$ and $\angle Z$ are concurrent.
- $\star$ $\mathcal Q$ has an incircle $\iff AB+CD=BC+DA\iff BE+BF=DE+DF\iff AE+CF=AF+CE$.

If $\triangle AEC$ and $\triangle AFB$ has an common $A$-excircle, we say this circle is an *excircle* of $\mathcal Q$.

- $\star$ $\mathcal Q$ has an excircle $\iff AB+BC=CD+DA\iff AE+EC=AF+FC\iff BE+ED=BF+FD$.
