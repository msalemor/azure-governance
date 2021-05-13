# Azure Governance

## Azure Governance

- How do I name my resources in Azure?
  - Naming conventions
- What is tagging useful for? How do I tag my resources?
  - Tags
- How do I prevent the accidental deletion of resources? 
  - Locks
- How do I prevent from expensive resource of being created, for example?
  - Policies
- Who can create, manage, and access resources?
  - RBAC
- How can I manage multiple subscriptions?
  - Management groups

## Why Governance

- Control cost
- Meet compliance requirements
- Meet security requirements

## Governance Cloud Adoption Framework (CAF)

- https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/govern/guides/standard/

## Resource Hierarchy

```text
Management Group
 \
  Subscriptions
   \
    Resource Groups
     \
      Resources
```

- https://docs.microsoft.com/en-us/azure/governance/management-groups/overview#hierarchy-of-management-groups-and-subscriptions

## Naming conventions

- https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/resource-name-rules
- https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/azure-subscription-service-limits
- https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-best-practices/resource-naming

## Tags

- https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/tag-resources?tabs=json

## Locks

- https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/lock-resources?tabs=json

## Azure Policy

- https://docs.microsoft.com/en-us/azure/governance/policy/overview
- https://docs.microsoft.com/en-us/azure/governance/policy/tutorials/create-and-manage
- https://docs.microsoft.com/en-us/azure/governance/policy/tutorials/create-custom-policy-definition

## RBAC (Role based access control)

- https://docs.microsoft.com/en-us/azure/role-based-access-control/overview
- https://docs.microsoft.com/en-us/azure/role-based-access-control/quickstart-assign-role-user-portal
- https://docs.microsoft.com/en-us/azure/role-based-access-control/built-in-roles
- Video: https://youtu.be/Dzhm-garKBM
- https://docs.microsoft.com/en-us/azure/role-based-access-control/custom-roles

## Management Groups

- https://docs.microsoft.com/en-us/azure/governance/management-groups/overview

## ARM Templates (IaC)

- https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/overview

## Blue Prints

Blueprints are a declarative way to orchestrate the deployment of various resource templates and other artifacts such as:

- Role Assignments
- Policy Assignments
- Azure Resource Manager templates (ARM templates)
- Resource Groups

Reference:
- https://docs.microsoft.com/en-us/azure/governance/blueprints/overview
- https://docs.microsoft.com/en-us/azure/governance/blueprints/create-blueprint-portal

