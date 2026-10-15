# Zion Ochayon

**MLOps / ML Platform Engineer.** I build and scale production ML platforms on GPU clusters, and make them faster and cheaper to run.

### Recent work
- **MAPI AI**: led the core processing pipeline of a production geospatial ML platform for Israel's national mapping authority. Ray on Kubernetes (EKS) at ~95% GPU utilization; ~1 TB of imagery, 20M image patches and 200K Ray tasks; 30M raw detection polygons merged into 2M final ones in PostGIS-based post-processing.
- **SARP**: built the imagery-to-model-output workflow of a satellite-imagery ML platform: Airflow orchestration, Ray execution, EKS/Helm deployment, and an MLflow integration for model tracking and versioning.
- **AWS infrastructure**: authored all the Terraform for separate dev and prod accounts: EKS with GPU autoscaling, cross-account image promotion, CI/CD with rollback, centralized logging.

### Stack
Ray / KubeRay · Kubernetes / EKS · Helm · Karpenter · Terraform · AWS · Airflow · MLflow · Python · FastAPI · PostgreSQL / PostGIS · GDAL / Rasterio · Prometheus / Grafana · GitHub Actions

### About the code
My production work runs in client and government systems, so the code is private. I'm happy to walk through the architecture and the trade-offs in a call.

[LinkedIn](https://www.linkedin.com/in/zion-ochayon/)
