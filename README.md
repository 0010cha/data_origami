# data_origami_pointcloud
 
 🍵　origami pointcloud simulation data
 
 (2020/4/9)
 
---
 
■ 全ての領域からランダムに3000点サンプリングする方法の点群データ  
directory: data_origami/airplane/points/  
filename： airplane1440_allarea_output_%d.ply

- 複数枚が完全に折り重なっている領域でも、枚数分サンプリングしている
- メッシュの全ての領域からサンプリング
- サンプリング点数が一定

---

■　single view point からサンプリングする方法の点群データ  
directory: data_origami/airplane/points_sv/  
filename： airplane1440_sv_output_%d.ply

- 複数枚が完全に折り重なっている領域は、枚数分ではなく一枚分サンプリングしている
- 単一視点から見える領域のみ
- サンプリング点数が一定ではない
- 単一視点の位置は任意に設定できるが，このデータでは (x,y,z)=(-1,-1,3) に設定した

---

CloudCompare https://www.danielgm.net/cc/  
Blender https://www.blender.org/  
などで表示確認できます  
　　

![Screenshot from 2020-04-09 18-58-00](https://user-images.githubusercontent.com/11142225/78883298-4df6f480-7a94-11ea-8990-a99df993e485.png)  
⬆　airplane1440_allarea_output_1000.ply

　　　　
      
![Screenshot from 2020-04-09 18-56-43](https://user-images.githubusercontent.com/11142225/78883313-518a7b80-7a94-11ea-9689-df8215bc2304.png)      
⬆　airplane1440_sv_output_1000.ply
