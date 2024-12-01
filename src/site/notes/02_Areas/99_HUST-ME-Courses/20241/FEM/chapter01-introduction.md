---
{"dg-publish":true,"permalink":"/02-areas/99-hust-me-courses/20241/fem/chapter01-introduction/","created":"2024-09-09T09:36:33.862+07:00","updated":"2024-12-01T17:39:58.890+07:00"}
---


# 1. Fundemental of Finite element method (FEM)
## 1.1. Brief history of FEM
## 1.2. Advantages of FEM
## 1.3. Some finite element programs
![[Pasted image 20240914150159.png  \|Pasted image 20240914150159.png  ]]
## 1.4. Some applications of FEM


# 2. Review some fundamental theory about matrix
# 3. General step of FEM
## Step 1: Discretize and select the element types
- This step involves dividing the body into an equivalent system of finite elements with associated nodes and choosing the most appropriate element type to model most closely the actual physical behavior
## Step 2: Establish element equations
- Select a displacement function
- Define the strain-displacement and stress-strain relationships
- Derive teh element stiffness matrix and equations: $[k]\{q\}=\{f\}$
	- [b] Direct stiffness method
	- [b] Energy method (Minium total potential energy principle)
## Step 3: Assembling the element equations to obtain teh global equations: 
$$[K]\{Q\}=\{F\}$$
## Step 4: Invoking boundary conditions and solve for unknown DOF
## Step 5: Interpret and analyze the results.

# 4. Direct stiffness method - linear spring element 
![[Drawing 2024-09-14 16.34.55.excalidraw \| 800]]
![[Drawing 2024-09-14 16.40.53.excalidraw \| 800]]
- Solution 1: Cách làm chay thuần túy 
![Pasted image 20240915231433.png](/img/user/99_Meta/attachments/Pasted%20image%2020240915231433.png)
- Solution 2: Có sử dụng bảng nhưng vẫn phải tìm hết $[K]$
![[Pasted image 20240915231518.png \|Pasted image 20240915231518.png ]]
- Solution 3: Hỏi $[K]$ vị trí nào trả lời luôn
![Pasted image 20240915231533.png](/img/user/99_Meta/attachments/Pasted%20image%2020240915231533.png)

$\to$ cách làm mà hỏi k nào là ra luôn 
![Pasted image 20240909111123.png](/img/user/99_Meta/attachments/Pasted%20image%2020240909111123.png)

# 5. Boundary conditions
## Homogeneous Boundary Conditions

![Pasted image 20240929184626.png](/img/user/99_Meta/attachments/Pasted%20image%2020240929184626.png)
## Nonhomogeneous Boundary Conditions

![Pasted image 20240929184637.png](/img/user/99_Meta/attachments/Pasted%20image%2020240929184637.png)

# 6. Direct stiffness method for bar element
## Kéo
![Pasted image 20240929185959.png](/img/user/99_Meta/attachments/Pasted%20image%2020240929185959.png)
## Xoắn
![Pasted image 20240929190016.png](/img/user/99_Meta/attachments/Pasted%20image%2020240929190016.png)

# 8. Direct stiffness method for beam element

![Pasted image 20240929190152.png](/img/user/99_Meta/attachments/Pasted%20image%2020240929190152.png)
![Pasted image 20240929190207.png](/img/user/99_Meta/attachments/Pasted%20image%2020240929190207.png)

# 9. Direct stiffness method for electrical network
![Pasted image 20240929190245.png](/img/user/99_Meta/attachments/Pasted%20image%2020240929190245.png)

# 10. Direct stiffness method for heat conduction
![Pasted image 20240929211706.png](/img/user/99_Meta/attachments/Pasted%20image%2020240929211706.png)

# 11. Direct stiffness method for fluid flow
![Pasted image 20240929212110.png](/img/user/99_Meta/attachments/Pasted%20image%2020240929212110.png)
![Pasted image 20240929212133.png](/img/user/99_Meta/attachments/Pasted%20image%2020240929212133.png)
![Pasted image 20240929212152.png](/img/user/99_Meta/attachments/Pasted%20image%2020240929212152.png)
