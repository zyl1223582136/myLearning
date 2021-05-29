# 《AI算法工程师手册》

## 数学基础

### 线性代数

#### 基本知识

1. 矩阵的`F`范数：设矩阵$$A=(a_{i,j})_{m\times n}$$ ，则其`F` 范数为： $$||A||_F=\sqrt{\sum_{i,j}a_{i,j}^2}$$

2. 迹的性质
   1. $$A$$的`F` 范数等于$$AA^T$$ 的迹的平方根 
   2. $$A$$的迹等于$$A^T$$ 的迹
   3. $$tr(AB)=tr(BA)$$

#### 向量操作
1. 三维向量的叉积
   
   $$
   \vec{w}=\vec{u}\times\vec{v}=\left[
    \begin{matrix}
      \vec{i} & \vec{j} & \vec{k} \\
      u_x & u_y & u_z \\
      v_x & v_y & v_z
     \end{matrix}
     \right]
   $$

2. 