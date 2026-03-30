# System_design_for_fresher

## btvn

Dựng một cụm Kubernetes local bằng Minikube và triển khai một hệ thống giả lập gồm nhiều thành phần khác nhau. Hệ thống này phải sử dụng đầy đủ các loại workload và resource cơ bản nhưng theo hướng gần với production hơn.
Học viên cần triển khai:
Deployment cho application chính
ReplicaSet để hiểu cơ chế duy trì số lượng Pod
DaemonSet để chạy một Pod trên mỗi node
Job hoặc CronJob cho tác vụ nền
Service để expose nội bộ
ConfigMap để cấu hình ứng dụng
Secret để lưu thông tin nhạy cảm
Bind ConfigMap và Secret vào Pod dưới dạng environment variables
Có thể bổ sung Ingress nếu muốn nâng cao
