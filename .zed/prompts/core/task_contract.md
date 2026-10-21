<task_contract>
Task ID: {{task_id}}
Title: {{title}}
Objective: {{objective}}
{{#if acceptance_criteria}}
Acceptance Criteria:
{{#each acceptance_criteria}}
- {{this}}
{{/each}}
{{/if}}
{{#if constraints}}
Constraints:
{{#each constraints}}
- {{this}}
{{/each}}
{{/if}}
Write Scopes: {{write_scopes}}
</task_contract>