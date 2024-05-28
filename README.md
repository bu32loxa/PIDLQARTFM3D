# Physics-informed Deep Learning to quantify anomalies for real-time fault mitigation in 3D printing

PIDLQARTFM3D

In 3D printing processes, there are many thermal stress related defects that can have a significant negative impact on the shape
and size of the structure. Such anomalies in the heat transfer of the printing process need to be detected at an early stage.
Understanding heat transfer is crucial, and simulationmodels can offer insightswhile reducing the need for costly experiments.
Traditional numerical solvers for heat transfer can be complex to adapt to diverse printed part geometries, and their reliance on
predefined mathematical models limits their flexibility. Our physics-informed deep learning (PIDL) approach eliminates the
need for discretization, simplifying the analysis of complex geometries and enabling automation. The drawback of parametric
PIDL is their scalability for high-dimensional problems. Computational time, energy and cost of training prevent real-time
analysis. It often takes only a few seconds to print a single layer.We can show an energy efficient transfer and training strategy
to reduce the computational effort of PIDL significantly. The approach is able to quantify relevant effects of thermal stresses
and mitigate errors during selective laser melting (SLM). To this end, heat transfer is modelled, simulated and analysed using
high-dimensional data obtained from printing experiments with different geometries of metal components. The proposed
method is applied to the solving forward problem of heat transfer prediction. The governing results are based on the heat
equation, which is integrated into a deep neural network (DNN).

https://link.springer.com/article/10.1007/s10489-024-05402-4
