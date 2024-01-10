# github-actions-library

## Helm Validation

inputs: 
- template_path: 
    description: 'path to template' 
    required: true 
- report_full_template: 
    description: 'Indicated if the full template should be posted to github comment. Consider switchit it off for massive charts' 
    default: true 
    required: false 
- lint_args: 
    description: 'Adds additional arguments to "helm lint" command' 
    required: false 
- template_args: 
    description: 'Adds additional arguments to "helm template" command' 
    required: false 
