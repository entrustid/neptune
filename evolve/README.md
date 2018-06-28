imported:
  resource-hr-csv.xml

but don't import the following tasks:
  task-hr-import.xml
  task-hr-recon.xml
  task-hr-livesync.xml
  
imported:
  resource-openldap.xml (need to work to connect to a real server)
    the following types were added to the resource:
      ACCOUNT -> inetOrgPerson
      ENTITLEMENT -> groupOfNames
      ENTITLEMENT -> posixGroup

Imported:
  role-meta-functional.xml
  role-meta-project.xml

Imported:
  object-template-org.xml
  object-template-user.xml
  roles.xml

  org-users.xml
  role-catalog.xml

Quick Start:
  import resources:
    resource-openldap.xml

  import org-roles-users
    shortcut-role-org-user.xml

  import resource:
    resource-hr.xml
