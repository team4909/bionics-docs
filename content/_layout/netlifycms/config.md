---
netlifycms_content_folder: "content"
outputs:
- netlifyyaml
url: /admin/config.yml
---
backend:
  name: "github"
  repo: "TechplexEngineer/bionics-docs"
  branch: "main"
  open_authoring: true

# Media files will be stored in the repo under images/uploads
media_folder: "static/images/uploads"
# The src attribute for uploaded media will begin with /images/uploads
public_folder: "/images/uploads" 
<!-- publish_mode: editorial_workflow -->