# Public repository disclosure

The repository is a dedicated ciphertext-only attestation repository. GitHub may publicly expose workflow YAML, repository owner/name/numeric ID, commit and workflow/run metadata, age public recipient, ciphertext release assets, ciphertext artifact names/sizes/digests, plaintext output archive digest, SLSA and custom research attestation metadata (including method/formula descriptions, parameter and parent/code/dependency digests and aggregate counts).

Producer source, real parent arrays, features, query IDs, ROI contents, matched memberships and result archives are never committed or uploaded in plaintext. Producer code and input are separately age-encrypted before upload. Plaintext is processed only inside the ephemeral GitHub-hosted runner and local protected staging. Private age identity is kept outside the repository/report directories and copied only through the repository secret mechanism; never logged or released.

Public metadata is still observable even when ciphertext remains confidential. Existing Stage3A historical trust stays D. No model or causal intervention is authorized.
