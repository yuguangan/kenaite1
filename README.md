# kenaite1
finish
/clear,all
/prep7
!定义材料参数
!!!!DN1000
ET,1,SHELL93						    
mp,ex,1,20e9
mp,ey,1,10e9
mp,ez,1,10e9
mp,gxy,1,6.9e9
mp,gxz,1,6.9e9
mp,gyz,1,6.9e9
mp,prxy,1,0.3
mp,prxz,1,0.3
mp,pryz,1,0.158
mp,dens,1,1800*28/21

!!!!DN900
mp,ex,2,20e9
mp,ey,2,10e9
mp,ez,2,10e9
mp,gxy,2,6.9e9
mp,gxz,2,6.9e9
mp,gyz,2,6.9e9
mp,prxy,2,0.3
mp,prxz,2,0.3
mp,pryz,2,0.158
mp,dens,2,1800*26/19



!!!!DN800
mp,ex,3,20e9
mp,ey,3,10e9
mp,ez,3,10e9
mp,gxy,3,6.9e9
mp,gxz,3,6.9e9
mp,gyz,3,6.9e9
mp,prxy,3,0.3
mp,prxz,3,0.3
mp,pryz,3,0.158
mp,dens,3,1800*24/17

!!!!DN700
mp,ex,4,20e9
mp,ey,4,10e9
mp,ez,4,10e9
mp,gxy,4,6.9e9
mp,gxz,4,6.9e9
mp,gyz,4,6.9e9
mp,prxy,4,0.3
mp,prxz,4,0.3
mp,pryz,4,0.158
mp,dens,4,1800*20/13

!!!!DN500
mp,ex,5,20e9
mp,ey,5,10e9
mp,ez,5,10e9
mp,gxy,5,6.9e9
mp,gxz,5,6.9e9
mp,gyz,5,6.9e9
mp,prxy,5,0.3
mp,prxz,5,0.3
mp,pryz,5,0.158
mp,dens,5,1800*16/9


!!!!DN400
mp,ex,6,20e9
mp,ey,6,10e9
mp,ez,6,10e9
mp,gxy,6,6.9e9
mp,gxz,6,6.9e9
mp,gyz,6,6.9e9
mp,prxy,6,0.3
mp,prxz,6,0.3
mp,pryz,6,0.158
mp,dens,6,1800*16/9

!!!!DN300
mp,ex,7,20e9
mp,ey,7,10e9
mp,ez,7,10e9
mp,gxy,7,6.9e9
mp,gxz,7,6.9e9
mp,gyz,7,6.9e9
mp,prxy,7,0.3
mp,prxz,7,0.3
mp,pryz,7,0.158
mp,dens,7,1800*14/7


!!!!DN250
mp,ex,8,20e9
mp,ey,8,10e9
mp,ez,8,10e9
mp,gxy,8,6.9e9
mp,gxz,8,6.9e9
mp,gyz,8,6.9e9
mp,prxy,8,0.3
mp,prxz,8,0.3
mp,pryz,8,0.158
mp,dens,8,1800*12/5


!!!!DN200
mp,ex,9,20e9
mp,ey,9,10e9
mp,ez,9,10e9
mp,gxy,9,6.9e9
mp,gxz,9,6.9e9
mp,gyz,9,6.9e9
mp,prxy,9,0.3
mp,prxz,9,0.3
mp,pryz,9,0.158
mp,dens,9,1800*12/5

!!!!DN150
mp,ex,10,20e9
mp,ey,10,10e9
mp,ez,10,10e9
mp,gxy,10,6.9e9
mp,gxz,10,6.9e9
mp,gyz,10,6.9e9
mp,prxy,10,0.3
mp,prxz,10,0.3
mp,pryz,10,0.158
mp,dens,10,1800*11/4

!!!!DN100
mp,ex,11,20e9
mp,ey,11,10e9
mp,ez,11,10e9
mp,gxy,11,6.9e9
mp,gxz,11,6.9e9
mp,gyz,11,6.9e9
mp,prxy,11,0.3
mp,prxz,11,0.3
mp,pryz,11,0.158
mp,dens,11,1800*11/4



r,1,0.021			!1000
r,2,0.019			!900
r,3,0.017			!800
r,4,0.013			!700
r,5,0.009			!500
r,6,0.009			!400
r,7,0.007			!300
r,8,0.005			!250
r,9,0.005			!200
r,10,0.004			!150
r,11,0.004			!100

!第一根主管
cswpla,11,0,1,1
cswpla,12,1,1,1
k,1,1/2,0,0
k,2,1/2,0,4.101
k,3,0.9/2,0,4.101+0.3
k,4,0.9/2,0,4.101+0.3+3.198
k,5,0.8/2,0,4.101+0.3+3.198+0.3
k,6,0.8/2,0,4.101+0.3+3.198+0.3+1.8
k,7,0.7/2,0,4.101+0.3+3.198+0.3+1.8+0.3
k,8,0.7/2,0,4.101+0.3+3.198+0.3+1.8+0.3+1.7
k,9,0.5/2,0,11.999       !4.101+0.3+3.198+0.3+1.8+0.3+1.7+0.3
k,10,0.5/2,0,13.05      !4.101+0.3+3.198+0.3+1.8+0.3+1.7+0.3+1.051
k,11,0.4/2,0,13.35      !4.101+0.3+3.198+0.3+1.8+0.3+1.7+0.3+1.051+0.3
k,12,0.4/2,0,15.4  !4.101+0.3+3.198+0.3+1.8+0.3+1.7+0.3+1.051+0.3+2.05
k,13,0.3/2,0,17.577   !4.101+0.3+3.198+0.3+1.8+0.3+1.7+0.3+1.051+0.3+2.05+0.3+1.877
k,14,0,0,0
k,15,0,0,1
*do,i,1,12
l,i,i+1
*enddo
arotat,all,,,,,,14,15
alls
cm,area1,area		!定义面的组
lsel,u,line,,all


!第一根下支管
wpcsys,-1,0
csys,0
wpoffs,0,0,1.717
wprota,0,0,90 
cswpla,14,1,1,1
cswpla,13,0,1,1 
*get,t1,kp,,num,max 
k,t1+1,0.25/2,0,0
k,t1+2,0.25/2,0,1.457
k,t1+3,0.2/2,0,1.457+0.15
k,t1+4,0.2/2,0,1.457+0.15+0.6
k,t1+5,0.15/2,0,1.457+0.15+0.6+0.15
k,t1+6,0.15/2,0,1.457+0.15+0.6+0.15+1.08
k,t1+7,0,0,0
k,t1+8,0,0,7
*do,i,t1+1,t1+5
l,i,i+1
*enddo
arotat,all,,,,,,t1+7,t1+8
lsel,u,line,,all  
 

!第一根上支管
wpcsys,-1,0
csys,0
wpoffs,0,0,2.461
wprota,0,0,-90 
cswpla,16,1,1,1
cswpla,15,0,1,1 
*get,t1,kp,,num,max 
k,t1+1,0.2/2,0,0
k,t1+2,0.2/2,0,0.881
k,t1+3,0.15/2,0,0.881+0.097
k,t1+4,0.15/2,0,0.881+0.097+0.507
k,t1+5,0,0,0
k,t1+6,0,0,5
*do,i,t1+1,t1+3
l,i,i+1
*enddo
arotat,all,,,,,,t1+5,t1+6
lsel,u,line,,all


!第2根上支管
wpcsys,-1,0
csys,0
wpoffs,0,0,3.9
wprota,0,0,-90 
cswpla,18,1,1,1
cswpla,17,0,1,1
*get,t1,kp,,num,max 
k,t1+1,0.25/2,0,0
k,t1+2,0.25/2,0,1.463
k,t1+3,0.2/2,0,1.463+0.15
k,t1+4,0.2/2,0,1.463+0.15+0.65
k,t1+5,0.15/2,0,1.463+0.15+0.65+0.1
k,t1+6,0.15/2,0,1.463+0.15+0.65+0.1+1.4
k,t1+7,0
k,t1+8,0,0,1
*do,i,t1+1,t1+5
l,i,i+1
*enddo
arotat,all,,,,,,t1+7,t1+8
lsel,u,line,,all


!第3根上支管
wpcsys,-1,0
csys,0
wpoffs,0,0,6.475
wprota,0,0,-90 
cswpla,20,1,1,1
cswpla,19,0,1,1
*get,t1,kp,,num,max 
k,t1+1,0.3/2,0,0
k,t1+2,0.3/2,0,2.438
k,t1+3,0.25/2,0,2.438+0.15
k,t1+4,0.25/2,0,2.438+0.15+0.788
k,t1+5,0.2/2,0,2.438+0.15+0.788+0.15
k,t1+6,0.2/2,0,2.438+0.15+0.788+0.15+0.85
k,t1+7,0.15/2,0,2.438+0.15+0.788+0.15+0.85+0.1
k,t1+8,0.15/2,0,2.438+0.15+0.788+0.15+0.85+0.1+0.655
k,t1+9,0,0,0
k,t1+10,0,0,1
*do,i,t1+1,t1+7
l,i,i+1
*enddo
arotat,all,,,,,,t1+9,t1+10
lsel,u,line,,all


!第4根上支管
wpcsys,-1,0
csys,0
wpoffs,0,0,6.475+2.791
wprota,0,0,-90 
cswpla,22,1,1,1
cswpla,21,0,1,1
*get,t1,kp,,num,max 
k,t1+1,0.3/2,0,0
k,t1+2,0.3/2,0,2.295
k,t1+3,0.25/2,0,2.295+0.15
k,t1+4,0.25/2,0,2.295+0.15+0.8
k,t1+5,0.2/2,0,2.295+0.15+0.8+0.15
k,t1+6,0.2/2,0,2.295+0.15+0.8+0.15+0.85
k,t1+7,0.15/2,0,2.295+0.15+0.8+0.15+0.85+0.1
k,t1+8,0.15/2,0,2.295+0.15+0.8+0.15+0.85+0.1+1.269
k,t1+9,0,0,0
k,t1+10,0,0,1
*do,i,t1+1,t1+7
l,i,i+1
*enddo
arotat,all,,,,,,t1+9,t1+10
lsel,u,line,,all




csys,20
asel,s,loc,x,0,0.3/2
csys,18
asel,a,loc,x,0,0.25/2
csys,16
asel,a,loc,x,0,0.2/2
csys,21
arsym,x,all,,,0,0


!第5根上支管
wpcsys,-1,0
csys,0
wpoffs,0,0,6.475+2.791+2.791
wprota,0,0,-90 
cswpla,24,1,1,1
cswpla,23,0,1,1


!第6根上支管
wpcsys,-1,0
csys,0
wpoffs,0,0,6.475+2.791+2.791+2.575
wprota,0,0,-90 
cswpla,26,1,1,1
cswpla,25,0,1,1


!第7根上支管
wpcsys,-1,0
csys,0
wpoffs,0,0,6.475+2.791+2.791+2.575+1.439
wprota,0,0,-90 
cswpla,28,1,1,1
cswpla,27,0,1,1

wpcsys,-1,0
csys,0
csys,14
asel,,loc,x,0,0.25/2
csys,0
AGEN,2,all, , , , ,2.183, ,0 


  

csys,14
asel,,loc,x,0,0.25/2
csys,0
AGEN,2,all, , , , ,2.183+2.575, ,0 


csys,14
asel,,loc,x,0,0.25/2
csys,0
AGEN,2,all, , , , ,2.183+2.575+2.791, ,0 


csys,14
asel,,loc,x,0,0.25/2
csys,0
AGEN,2,all, , , , ,2.183+2.575+2.791+2.791, ,0 

csys,14
asel,,loc,x,0,0.25/2
csys,0
AGEN,2,all, , , , ,2.183+2.575+2.791+2.791+2.575, ,0 

csys,14
asel,,loc,x,0,0.25/2
csys,0
AGEN,2,all, , , , ,2.183+2.575+2.791+2.791+2.575+2.183, ,0 

wpcsys,-1,0
csys,0
wpoffs,0,0,16.814
wprota,0,0,90 
cswpla,30,1,1,1
cswpla,29,0,1,1 
alls


!!!!!!梁点
wpcsys,-1,0
csys,0
wpoffs,0,0,4.985
asbw,all
csys,4
 ksel,,loc,z,0
 *get,k1,kp,,num,max 
 wpcsys,-1,0
 wpoffs,0,0,4.985+8.561
asbw,all
csys,4
 ksel,,loc,z,0
 *get,k2,kp,,num,max
 
 
 wpcsys,-1,0
csys,0
wprota,0,0,-90
wpoffs,0,0,2.122    
  asbw,all 
  csys,4
 ksel,,loc,z,0  
  k3=420
 k4=424
 k5=428
 k6=432
 k7=436
 
 
  wpcsys,-1,0
csys,0
wprota,0,0,-90
wpoffs,0,0,0.761
asbw,all
 csys,4
 ksel,,loc,z,0 
 !!!!!!!!质量点
 m1=440     !!!!!!!大的
 m2=444
 m3=448
 m4=452
 m5=456
 m6=560
 m7=464
 
wpoffs,0,0,0.952
asbw,all
 csys,4
 ksel,,loc,z,0     !!!!大的
 m8=468
 m9=472
 m10=476
m11=480
m12=484

wpoffs,0,0,1.142
asbw,all
 csys,4
 ksel,,loc,z,0
 
 m13=488
 m14=492
 m15=496
 m16=500
 m17=504

wpoffs,0,0,1.142
asbw,all
 csys,4
 ksel,,loc,z,0
 m18=508
 m19=512
 m20=516
 
 
 wpoffs,0,0,0.845
asbw,all
 csys,4
 ksel,,loc,z,0
 m21=520
 m22=524
 m23=528
 
 
  wpcsys,-1,0
csys,0
wprota,0,0,90
wpoffs,0,0,0.75
asbw,all
 csys,4
 ksel,,loc,z,0 
 
 !!!!!质量点小的
 mm1=532
 mm2=536
 mm3=540
 mm4=544
 mm5=548
 mm6=552
 mm7=556

  wpcsys,-1,0
csys,0
wprota,0,0,90
wpoffs,0,0,1.028
asbw,all
 csys,4
 ksel,,loc,z,0  
 
  mm8=560
 mm9=564
 mm10=568
 mm11=572
 mm12=576
 mm13=580
 mm14=584

wpcsys,-1,0
csys,0
wprota,0,0,90
wpoffs,0,0,1.78
asbw,all
 csys,4
 ksel,,loc,z,0  
 
  mm15=588
 mm16=592
 mm17=596
 mm18=600
 mm19=604
 mm20=608
 mm21=612
 
 
 et,2,mass21
KEYOPT,2,3,2


r,9,36
r,10,23
 
 
 
 
 
 
 
 
 
 
 
 
 

 
