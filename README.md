เช็คชื่อ 
Week 4 https://forms.gle/3Apfu8EHiadf1JMv7
# Home work Week 4
1. Deploy Jenkins and Grafana on kubernetes.
2. Create github repo with https://github.com/user-name/b5124817-xxxxx
   - Create folder jenkins and grafana
   - Add file
     - deployment.yaml
     - service.yaml
     - pv.yaml
     - pvc.yaml
     - ingress.yaml
     - Screen capture web browser
   - if deploy fail -> capture log on kubernetes and write detail of error.
3. Don't forget map domain in file hosts.
---
## ผลการรันระบบ Kubernetes

### สถานะ Pod ใน Cluster
แสดงผลลัพธ์คำสั่ง `kubectl get pods -A`

![Pods](https://drive.google.com/file/d/1dyY2q97Ifl6EmZCnjMIeq4p758ZZETul/view?usp=sharing)

### หน้า Jenkins Dashboard
แสดงหน้า Dashboard ของ Jenkins หลังจากติดตั้งสำเร็จ

![Jenkins](https://drive.google.com/file/d/13JWXbbNMCU8BYSv_blSv6dh3b-E89g65/view?usp=sharing)
![Jenkins](https://drive.google.com/file/d/1i2dXL1JiOPTRWXvHFn9aSRfMpPSgB-K2/view?usp=sharing)
---

### หน้าเข้าสู่ระบบ Grafana
แสดงหน้า Login ของ Grafana สำหรับระบบ Monitoring

![Grafana](https://drive.google.com/file/d/1MapNsTtdOtI2ev80_xuBYp3AmNshaA3P/view?usp=sharing)
