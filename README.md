Encode USERNAME and PASSWORD of Postgres using following commands:
echo -n "postgresadmin" | base64
echo -n "admin123" | base64

Execute first the command:
kubectl apply -f postgres-sonar.yaml

Execute second command:
kubectl apply -f sonarqube.yaml
