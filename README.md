# 📚 Docker e Kubernetes Objetivos

- Criar pipelines para build e publicação de imagens Docker
- Publicar imagens em Container Registry (AWS ECR)
- Automatizar deploys no Kubernetes com Kustomize
- Implementar estratégias avançadas de deploy (Blue/Green e Canary)
- Configurar health checks e probes no Kubernetes

## Anotações importantes

- **AWS Learner Lab**: Usar sempre `--profile fiapaws` nos comandos AWS CLI
- **Cluster**: Nome do cluster: `cicd-lab`
- **Limitações**: Máximo 9 instâncias EC2 e 32 vCPU concorrentes
- **Instance Types**: Apenas nano, micro, small, medium, large
- **Regiões**: us-east-1 ou us-west-2
- **Credenciais**: Usar GitHub Secrets para armazenar AWS Access Keys
- **Sessão**: Renovar credenciais quando a sessão do Learner Lab expirar
- **Limpeza**: Sempre deletar recursos após a aula para preservar o budget
- **Secrets**: Nunca commitar credenciais no código

**Yml Adaptado para rodar localmente no motoserver + minikube** para não ter custos com nuvem no aprendizado.
