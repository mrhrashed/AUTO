# AUTO

Custom adder library for the AUTO framework. Download the entire library form google drive: https://drive.google.com/drive/folders/19s_NPQx6zneyzXnukU162PsVVk1c-WV1?usp=sharing

Naming style of library directories: 
    
    Each file "k_lim=X.zip" contains the custom adder library for kernel limit of X. 

Naming style of adder netlists: 
    
    An adder netlist named "lim_U_acc_V_b_W_X_Y.blif" represents that the kernel limit for the adder is 'U', actual kernel weight of the adder is 'V', and the custom adder kernel consists of three columns W, X, and Y height (#of partial products per column) from right. For instance, the netlist "lim_15_acc_12_b_2_3_1.blif" represents an adder kernel with limit 15, actual weight 12 and consists of 2, 3 and 1 partial products respectively in different columns of the kernel. 

