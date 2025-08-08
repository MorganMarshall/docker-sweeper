## 🧹 Docker Sweeper

Keep your Docker environment clean and tidy by removing unused volumes and images — freeing up disk space and improving performance!

---

## Quick Cleanup Commands

Run these commands to safely remove **all unused Docker volumes and images**:

```bash
# Remove all unused Docker images and volumes (not used by any container)
docker volume prune -f && docker image prune -a -f
