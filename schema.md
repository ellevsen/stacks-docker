swarm-manager:
  - traefik
  - portainer
  - n8n_editor
  - portfolio
  - jobs-dashboard

swarm-worker-1:
  - n8n_worker
  - n8n_webhook
  - redis
  - rabbitmq
  - postgres
  - minio
  - evolution

main network:
    - swarm_public