# ArchSetu pre-commit hook

Run ArchSetu's deterministic static analysis — dead code detection, health
score, and security risk scanning — automatically before every commit.
No AI, no network calls on your source code; everything runs locally.

## Usage

Add to your `.pre-commit-config.yaml`:

    repos:
      - repo: https://github.com/vishalkelur28-cyber/archsetu-pre-commit-hook
        rev: v0.1.0
        hooks:
          - id: archsetu

Then run:

    pre-commit install

Every commit will now print ArchSetu's analysis results in your terminal.

## Learn more

Full platform: https://www.archsetu.com
