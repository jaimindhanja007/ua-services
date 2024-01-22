# Steps to setup Helm chart for Grafana

- Install Helm
- Use command: helm create *name of the helmchart* and create one helm chart
- Using command: tree *name of helmchart* we can see the helm chart created
- Modify the chart.yaml and values.yaml 
- In Image, we modify the repository to our image and the port number to the port number we have used for the image.
- Use command: helm template *name of the helmchart* and check all the yaml files. This is where your helm chart is created successfully. For deployments and upgrades check the link in the next step.
- For any help refer: [Link](https://jhooq.com/building-first-helm-chart-with-spring-boot/)
