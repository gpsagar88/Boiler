# Boiler
Scientific project
----------------------
In very first work we select vapour quality for searching of appropriate probabilty equation. The reason is following, vapour quality easy to observe with optical methods and bubbles quite descriptive to understand variotional approach.  In fact, we are searching for complex function describing probability \{0;1\} of volume fraction for each point of water tank. In particular, there is a conditional probability for each pixel of image in case of known state of all pixles at previous moment of time
 \begin{equation}\label{eq:conditional_p}
x_{t} = Pr( x_{t} \mid  x_{<t},z_{<t}),
\end{equation}
  where x pixel value for every image part, t -time, z- number of random variables with the normal distribution. The value of each pixel $x_{i} $ derived of particular liquid volume fraction attributed as 0 if 100\% vapour or 1 i 100\%liquid observed. The number of random variables present influene of chaotic nature. This is adjusting value for optimization. Moreover, this is a part of parametrization of VRNN method[]. In addition, no one knows how much random source observed in particular boiling regime.
 The probability is approximating for region near the heating wall. We have made this constrain because we gain the attention to heattransfer. In case of calculating flow vapour quality area location and size should be varied.
