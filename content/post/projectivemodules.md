+++
title = "Projective, injective and flat modules"
date = "2017-02-18"
tags = [ "math" ]
topics = [ "math" ]
+++

# Definitions

An R-module \\(D\\) is:

1.  **Projective** if \\(Hom(D, -)\\) is an exact functor.
2.  **Injective** if \\(Hom(-,D)\\) is an exact functor.
3.  **Flat** if \\(D \otimes -\\) is an exact functor.


# Characterization

We know that \\(Hom(D,-)\\) and \\(Hom(-,D)\\) are left-exact and that \\(D\otimes -\\) is right-exact; so for them to be exact, we only need:

-   A module \\(D\\) is **projective** when every \\(f : B \longrightarrow C\\) surjective induces \\((f\circ\_) :Hom(D,B) \longrightarrow Hom(D,C)\\) surjective.
    
    ![img](//raw.githubusercontent.com/M42/m42.github.io/images/projective.jpeg)

-   A module \\(D\\) is **injective** when \\(f : A \longrightarrow B\\) surjective induces \\((\_\circ f) : Hom(B,D) \longrightarrow Hom(A,D)\\) surjective.
    
    ![img](//raw.githubusercontent.com/M42/m42.github.io/images/injective.jpeg)

-   A module \\(D\\) is **flat** when \\(f : A \longrightarrow B\\) injective induces \\(f' : D\otimes A \longrightarrow D \otimes B\\) injective.
