# data_origami_pointcloud
 
 🍵　origami pointcloud simulation data
 
 
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
