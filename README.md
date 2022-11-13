# tafun-alm-workshop-cfg
TA Fundamentals ALM Workshop Configuration repository

# Workshop

1. Create a gh-pages branch that is empty
2. Install Helm locally by downloading one of the latest releases https://github.com/helm/helm/releases and setting up your environment
3. On main branch you can execute `helm create <chart-name>` to generate a default chart
4. The github action that we will be using requires the chart to be nested in a /charts folder by default
5. Update values.yaml to have your image in it 