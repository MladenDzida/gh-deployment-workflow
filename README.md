# gh-deployment-workflow
A simple GitHub Actions workflow for deploying a static website to GitHub Pages. (https://roadmap.sh/projects/github-actions-deployment-workflow)

deploy configurations are stored in .github/workflows/deploy.yml:
<ul>
  <li>on each push that contains changes to the index.html, the github actions start the deploy proces:
    <ol>
      <li>Code checkout on the remote</li>
      <li>Configuring Github pages</li>
      <li>Uploading the static site to Github pages</li>
      <li>Deploy</li>
    </ol>
  </li>
  <li>code is deployed on ubuntu</li>
</ul>

deployed index.html: https://mladendzida.github.io/gh-deployment-workflow/
