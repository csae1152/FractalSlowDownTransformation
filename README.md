# Fractal Slow Down Transformation
A novel algorithm for markov chain lumpability in the context of backpropagation.

https://farmdiagnosis.herokuapp.com/ you can see an online demo of the results here.

It has been demonstrated that higher order recurrent neu-
ral networks exhibit an underlying fractal attractor as an
artifact of their dynamics. These fractal attractors offer a very effcent mechanism to encode visual memories in a neu-
ral substrate, since even a simple 9 weight network can
encode a very large set of different images.
The main problem in this memory model, which so far has
remained unaddressed, is how to train the networks to learn
these different attractors. Following other neural training
methods this paper proposes a Gradient Descent method
to learn the attractors. The method is based on an error
function which examines the efects of the current network
transform on the desired fractal attractor. It is tested across
a bank of different target fractal attractors and at different
noise levels. The results show positive performance across
three error measures.
