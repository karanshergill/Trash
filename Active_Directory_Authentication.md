graph TB
  AD[Active Directory Authentication]
  NTLM[NTLM]
  Kerberos[Kerberos]
  LDAP[LDAP]
  RADIUS[RADIUS]

  AD --> NTLM
  AD --> Kerberos
  AD --> LDAP
  AD --> RADIUS
