# Argocd Kubernetes Gitops Tutorial

This repo contains all the code needed to follow along with our **[YouTube Tutorial](https://link)**

## API Calls

Here are commands that you can use to add grades to the Grade Submission API. **Windows Users should use Git Bash**.

```bash
curl -X POST http://localhost:31000/grades \
  -H "Content-Type: application/json" \
  -d '{"name": "Harry", "subject": "Defense Against Dark Arts", "score": 95}'

curl -X POST http://localhost:31000/grades \
  -H "Content-Type: application/json" \
  -d '{"name": "Ron", "subject": "Charms", "score": 82}'

curl -X POST http://localhost:31000/grades \
  -H "Content-Type: application/json" \
  -d '{"name": "Hermione", "subject": "Potions", "score": 98}'
```

To verify, you can get all grades with:
```bash
curl http://localhost:31000/grades
```

## Kubernetes Training

If you found this guide helpful, check out our [Kubernetes Training course](https://kubernetestraining.io/)