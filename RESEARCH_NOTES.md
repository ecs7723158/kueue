# 🔬 Research & Engineering Notes: kueue

- **Date**: 2026-09-24 21:30:12
- **Branch**: `research/notes`
- **Upstream Repository**: [kubernetes-sigs/kueue](https://github.com/kubernetes-sigs/kueue)
- **Stargazers**: ★ 2969
- **Summary**: Kubernetes-native Job Queueing and Batch Quota Management

---

## 📌 Architectural Breakdown
仔細看了 kueue 在 K8s 原生 job queueing 與 batch quota 管理的運作機制，它的 cohort 與 multi-tenancy resource borrowing 設計非常成熟。

## ⚙️ Engineering Evaluation
對於 AI/ML 大規模分散式訓練與批次推論任務的優先權排程、搶占控制做得極度嚴密，且原生支援 DRA 與 Cluster Autoscaler。

## 🚀 Action Items & Next Steps
持續在 research/notes 分支推進，實測它的 fair-sharing 演算法與 local queue 行為，確保能跟目前研究的 autoscaling policy 順利對接。
