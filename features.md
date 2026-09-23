# Distinctive Discord Server Features

These features are unusual compared with a standard Discord server and are documented in this repository.

1. **Constitutional governance system**  
   A formal constitution with an elected five-member Council, ranked-choice/STV elections, recall procedures, appeals, and defined powers.  
   Sources: [SERVER GOVERNANCE & CONSTITUTION.md](SERVER%20GOVERNANCE%20%26%20CONSTITUTION.md), [member-guide.md](member-guide.md)

2. **Independent Archivist role**  
   The technical server owner is separated from political authority, with succession planning, recovery duties, and limits on emergency powers.  
   Sources: [SERVER GOVERNANCE & CONSTITUTION.md](SERVER%20GOVERNANCE%20%26%20CONSTITUTION.md), [member-guide.md](member-guide.md)

3. **Human-only creative work policy**  
   Generative AI may not be used to create, revise, critique, or train on server-shared creative work.  
   Sources: [community-standards.md](community-standards.md), [SERVER GOVERNANCE & CONSTITUTION.md](SERVER%20GOVERNANCE%20%26%20CONSTITUTION.md)

4. **Private Council reporting and ticket system**  
   Members can contact the Council privately, with safeguards preventing the person being reported from participating in the review.  
   Sources: [member-guide.md](member-guide.md), [discord/seed-content/reporting.md](discord/seed-content/reporting.md)

5. **Repository-managed Discord configuration**  
   Channels, roles, permissions, moderation rules, and content are defined declaratively in manifests and reconciled automatically with the live server.  
   Sources: [development/development-plan.md](development/development-plan.md), [tools/hwc-discord/README.md](tools/hwc-discord/README.md)

6. **Automated drift detection and disaster recovery**  
   The system validates live server state, creates snapshots, detects configuration drift, and supports reconstruction from the repository manifest.  
   Sources: [tools/hwc-discord/README.md](tools/hwc-discord/README.md), [discord/snapshots/README.md](discord/snapshots/README.md)

7. **Repository-backed seed content**  
   Welcome messages, guides, standards, and reporting instructions are version-controlled, published, pinned, and updated through tooling.  
   Sources: [tools/hwc-discord/README.md](tools/hwc-discord/README.md), [discord/seed-content/welcome.md](discord/seed-content/welcome.md)

8. **Automated Constitution discussion forum**  
   A script creates or updates forum threads for individual Constitution sections and tracks their Discord thread IDs.  
   Source: [tools/hwc-discord/README.md](tools/hwc-discord/README.md)

9. **Opt-in, age-gated mature-content area**  
   A dedicated "Red Room" is hidden behind an explicit Mature Content role and age-gating controls.  
   Sources: [proposed-channels.md](proposed-channels.md), [discord/seed-content/start-here.md](discord/seed-content/start-here.md)

10. **Structured, opt-in workshop and critique system**  
    Critique is voluntary, rights-protecting, and governed by explicit participation and feedback boundaries.  
    Sources: [discord/seed-content/workshop-guide.md](discord/seed-content/workshop-guide.md), [community-standards.md](community-standards.md)

11. **Formal financial transparency and conflict-of-interest rules**  
    Council members must publish financial summaries, disclose conflicts, recuse themselves, and cannot self-approve reimbursements.  
   Source: [SERVER GOVERNANCE & CONSTITUTION.md](SERVER%20GOVERNANCE%20%26%20CONSTITUTION.md)

12. **Explicit AI-training prohibition**  
    Server content may not be used to train AI systems, providing stronger content-rights protections than most community servers.  
    Sources: [community-standards.md](community-standards.md), [SERVER GOVERNANCE & CONSTITUTION.md](SERVER%20GOVERNANCE%20%26%20CONSTITUTION.md)

13. **Dedicated UI and permission-boundary testing**  
    The project includes disposable-server testing for channel visibility, role permissions, age gates, and governance boundaries.  
    Source: [development/server-ui-testing-plan.md](development/server-ui-testing-plan.md)
