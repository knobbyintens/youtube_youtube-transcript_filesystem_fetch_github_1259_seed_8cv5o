# Citation Audit Policy

1. A watch-list entry carries exactly one repository identifier in
   `owner/name` form. The identifier recorded in `catalogue/source_items.json`
   is what was originally published and must be preserved verbatim in the
   register.
2. Every identifier is resolved against the code hosting service before the
   register is published. Repository code moves between owners and names over
   time; confirm that a repository is genuinely gone before recording it as
   missing. A citation that resolves to a live repository is valid even if the
   address printed in the catalogue no longer serves content directly.
3. If the resolved repository is a fork of another project, it is not the
   upstream project. Record the entry as a fork and add it to the hold list for
   editorial review.
4. If an identifier cannot be resolved at all, record it as missing and add it
   to the hold list.
5. Every register row also records the episode's current title and channel as
   reported by the video platform, together with the canonical watch URL.
6. Registers are published to `reviews/citation_audit.csv` and hold lists to
   `reviews/hold_list.csv`; the desk also keeps the register in the editor's
   local workspace.
