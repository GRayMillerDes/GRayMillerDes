# Hi there, I'm Gary Miller 👋

<p align="center">
  <a href="https://www.linkedin.com/in/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <img src="https://img.shields.io/badge/Focus-Cloud_Native_%7C_DevOps_%7C_SRE-2563EB?style=for-the-badge" alt="Focus" />
  <img src="https://img.shields.io/badge/Kubernetes-Production--Ready-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes" />
  <img src="https://img.shields.io/badge/Security-Zero--Trust-10B981?style=for-the-badge&logo=vault&logoColor=white" alt="Zero Trust" />
</p>

---

### 🚀 About Me
Experienced **Senior SRE & Cloud Architect** specializing in multi-cloud enterprise architectures, GitOps continuous delivery, and Zero-Trust infrastructure automation. Passionate about building resilient, observable, and highly scalable cloud-native platforms.

- 🔭 **Focus Areas**: Multi-Cloud Infrastructure (AWS / Azure / GCP / Bare-Metal), Kubernetes, GitOps, Service Mesh.
- 🛡️ **Zero-Trust & Security**: External Secrets Operator (ESO), HashiCorp Vault, SPIFFE/SPIRE, Immutable Delivery.
- 📊 **SRE & Observability**: SLI/SLO Engineering, Prometheus, Grafana, Thanos, Distributed Tracing.
- ⚡ **Infrastructure as Code**: Terraform, Terragrunt, Ansible, ArgoCD, Helm.

---

### 🌟 Featured Open-Source Architectures

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">🛡️ <a href="https://github.com/GRayMillerDes/multicloud-cicd-zero-trust-architecture">Multi-Cloud CI/CD Zero-Trust Architecture</a></h3>
      <p align="center">
        <img src="https://img.shields.io/badge/Architecture-Enterprise_Blueprint-blue?style=flat-square" />
        <img src="https://img.shields.io/badge/Security-Zero--Trust_ESO-green?style=flat-square" />
      </p>
      <p>Enterprise Multi-Cloud CI/CD blueprint implementing <b>Zero-Trust secret delivery (External Secrets Operator)</b>, immutable deployment pipelines with Packer & Terraform, and non-interactive SRE automated incident diagnostics.</p>
      <ul>
        <li><b>Cloud Environments</b>: AWS, Azure, GCP & Hybrid Bare-Metal</li>
        <li><b>CI/CD Engine</b>: CloudBees / Jenkins / GitHub Actions with OIDC</li>
        <li><b>Secret Lifecycle</b>: Short-lived credentials, rotation, zero persistent tokens</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">⚡ <a href="https://github.com/GRayMillerDes/hybrid-gitops-sre-lab">Hybrid GitOps SRE Lab</a></h3>
      <p align="center">
        <img src="https://img.shields.io/badge/Platform-Kubernetes_v1.30+-blue?style=flat-square" />
        <img src="https://img.shields.io/badge/GitOps-ArgoCD-orange?style=flat-square" />
      </p>
      <p>A production-grade Kubernetes & GitOps sandbox demonstrating enterprise IaC patterns, ESO zero-trust synchronization across clouds, and end-to-end SRE observability suites.</p>
      <ul>
        <li><b>GitOps Stack</b>: ArgoCD Declarative App-of-Apps & Helm Charts</li>
        <li><b>Observability</b>: Prometheus, Grafana dashboards, Alertmanager</li>
        <li><b>Resilience</b>: Automated failover, health checks, SLO validation</li>
      </ul>
    </td>
  </tr>
</table>

---

### 🛠️ Tech Stack & Tooling

Usage: Security [-h] [-i] [-l] [-p prompt] [-q] [-v] [command] [opt ...]
    -i    Run in interactive mode.
    -l    Run /usr/bin/leaks -nocontext before exiting.
    -p    Set the prompt to "prompt" (implies -i).
    -q    Be less verbose.
    -v    Be more verbose about what's going on.
Security commands are:
    help                                 Show all commands, or show usage for a command.
    list-keychains                       Display or manipulate the keychain search list.
    list-smartcards                      Display available smartcards.
    default-keychain                     Display or set the default keychain.
    login-keychain                       Display or set the login keychain.
    create-keychain                      Create keychains and add them to the search list.
    delete-keychain                      Delete keychains and remove them from the search list.
    lock-keychain                        Lock the specified keychain.
    unlock-keychain                      Unlock the specified keychain. Unlocking the login keychain might succeed even if an incorrect password is presented, if other unlock factors are available.
    set-keychain-settings                Set settings for a keychain.
    set-keychain-password                Set password for a keychain.
    show-keychain-info                   Show the settings for keychain.
    dump-keychain                        Dump the contents of one or more keychains.
    create-keypair                       Create an asymmetric key pair.
    add-generic-password                 Add a generic password item.
    add-internet-password                Add an internet password item.
    add-certificates                     Add certificates to a keychain.
    find-generic-password                Find a generic password item.
    delete-generic-password              Delete a generic password item.
    set-generic-password-partition-list  Set the partition list of a generic password item.
    find-internet-password               Find an internet password item.
    delete-internet-password             Delete an internet password item.
    set-internet-password-partition-list Set the partition list of a internet password item.
    find-key                             Find keys in the keychain
    set-key-partition-list               Set the partition list of a key.
    find-certificate                     Find a certificate item.
    find-identity                        Find an identity (certificate + private key).
    delete-certificate                   Delete a certificate from a keychain.
    delete-identity                      Delete an identity (certificate + private key) from a keychain.
    set-identity-preference              Set the preferred identity to use for a service.
    get-identity-preference              Get the preferred identity to use for a service.
    create-db                            Create a db using the DL.
    export                               Export items from a keychain.
    import                               Import items into a keychain.
    export-smartcard                     Export items from a smartcard.
    cms                                  Encode or decode CMS messages.
    install-mds                          Install (or re-install) the MDS database.
    add-trusted-cert                     Add trusted certificate(s).
    remove-trusted-cert                  Remove trusted certificate(s).
    dump-trust-settings                  Display contents of trust settings.
    user-trust-settings-enable           Display or manipulate user-level trust settings.
    trust-settings-export                Export trust settings.
    trust-settings-import                Import trust settings.
    verify-cert                          Verify certificate(s).
    authorize                            Perform authorization operations.
    authorizationdb                      Make changes to the authorization policy database.
    execute-with-privileges              Execute tool with privileges.
    leaks                                Run /usr/bin/leaks on this process.
    error                                Display a descriptive message for the given error code(s).
    create-filevaultmaster-keychain      Create a keychain containing a key pair for FileVault recovery use.
    smartcards                           Enable, disable or list disabled smartcard tokens.
    translocate-policy-check             Check whether a path would be translocated.
    translocate-status-check             Check whether a path is translocated.
    translocate-original-path            Find the original path for a translocated path.
    requirement-evaluate                 Evaluate a requirement against a cert chain.
    filevault                            Handles FileVault specific settings and overrides.
    platformsso                          Handles Platform SSO specific settings and overrides.
Script: Python,: No such file or directory
Script started, output file is :
Script started, output file is :

Script done, output file is :

---

<p align="center">
  <i>“Automate everything, verify continuously, design for failure.”</i>
</p>
