The key contributions of this study include:

1. The development of various server push strategies which are evaluated to identify their
performance characteristics regarding several evaluation metrics. These strategies aim to
eliminate various issues of adaptive streaming.

2. The evaluation was performed on the popular Apache web server. Most of the existing
literature work evaluated HTTP and the server push feature in different web servers but
none of them performed the evaluation on Apache. To the best of our knowledge, this is
the first attempt leveraging and evaluating the server push feature of HTTP/2 on the most
widely used web server.

3. The implemented web interface aims to simplify and speed up the process of configuring
pushed resources on the Apache web server. To the best of our knowledge, this is the first
implementation which attempts to do that.

The paper is organised as follows. Initially, a detailed literature review about the
various concepts of the project and any related work is provided. Additionally, the paper describes
the design of the experimental setup and the design of the web interface. Following that, the paper
highlights the implementation of the various server push strategies and also gives details about the
implemented software. Moreover, in the Experimental Analysis section all the experiments
conducted along with their results are reported in great detail. Finally, the paper summarises the
findings and present some possible future work.