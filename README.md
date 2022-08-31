# MLCLSPSB_Instance
Instance for the MLCLSPSB

## Format

**N_Product** : $N$

**Cap**  : The data of the capacity of each resource in each period. The data format is as follow: 
$$
[C_{t_{1},r_{1}},C_{t_{2},r_{1}},\ldots,C_{T,r_{1}}]\\ \vdots \\
[C_{t_{1},R},C_{t_{2},R},\ldots,C_{T,R}]
$$

**Production_Time** : The data of the production time of each resource needed for the production of each item. The data format is as follow:
$$
[q_{i_{1},r_{1}},q_{i_{2},r_{2}},\ldots,q_{N,r_{1}}]\\
\vdots \\
[q_{i_{1},R},q_{i_{2},R},\ldots,q_{N,R}]
$$

**Order_Delay_TimeLimit** : The data of  the backorder time limitation of each item in each period. The data format is as follow: 
$$
[L_{i_{1},t_{1}},L_{i_{2},t_{1}},...,L_{i_{N},t_{1}} ]\\ \vdots \\ [L_{i_{1},t_{T}},L_{i_{2},t_{T}},...,L_{i_{N},t_{T}}]
$$


**Demand** : The data of the demand of each item in each period. The data format is as follow: 
$$
[[d_{i_{1},t_{1}},d_{i_{1},t_{2}},\ldots,d_{i_{1},T}],[d_{i_{2},t_{1}},d_{i_{2},t_{2}},\ldots,d_{i_{2},T}],\ldots,[d_{N,t_{1}},d_{N,t_{2}},\ldots,d_{N,T}]]
$$
**Setup_Time** : The data of the setup time of each item in each resource. The data format is as follow: 
$$
[st_{i_{1},r_{1}},st_{i_{2},r_{1}},\ldots,st_{N,r_{1}}]\\
\vdots \\
[st_{i_{1},R},st_{i_{2},R},\ldots,st_{N,R}]
$$
**Setup_Costs** : The data of the setup costs of each item in each resource. The data format is as follow:
$$
[sc_{i_{1},r_{1}},sc_{i_{2},r_{1}},\ldots,sc_{N,r_{1}}]\\
\vdots \\
[sc_{i_{1},R},sc_{i_{2},R},\ldots,sc_{N,R}]
$$
**Holding_Costs** : The data of the holding costs of each item. The data format is as follow:
$$
[h_{i_{1}},h_{i_{2}},\ldots,h_{N}]
$$
**Delay_Costs** : The data of the backorder costs of each item. The data format is as follow:
$$
[p_{i_{1}},p_{i_{2}},\ldots,p_{N}]
$$
**Assemble,Component,Quantity** : The data of the BOM. Each line corresponds to a assemble relationship with the data format as follow:
$$
[j,i,q_{ij}]
$$
**Substitution,Product,Cost,Quantity** : The data of the substitution. Each line corresponds to a substitution relationship with the data format as follow:
$$
[i,j,r_{ij},q_{ij}^{s}]
$$



