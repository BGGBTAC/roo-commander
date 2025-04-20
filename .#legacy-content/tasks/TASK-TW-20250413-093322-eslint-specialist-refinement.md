# Sub-Task: Refine Mode - 039-work-xf-eslint-specialist.mode.md

**Master Task:** project_journal/tasks/TASK-PM-20250413-090710-v7-mode-refinement.md
**Status:** Complete ✅
**Coordinator:** roo-commander
**Assigned To:** technical-writer
**Mode File:** 03x-worker/039-cross-functional/eslint-specialist/039-work-xf-eslint-specialist.mode.md

## Goal
Review and update the specified mode file to ensure consistency, completeness, and alignment with v7 standards and the hybrid context strategy, as detailed in `v7.0/future-planning/current-status-and-mode-refinement-plan.md` (Section 2, Step 29).

## Acceptance Criteria
- All standard sections from `v7.0/templates/mode_template.md` are present.
- Emoji is assigned/verified.
- Core content (Description, Capabilities, Workflow, Role Definition) is accurate and detailed.
- Custom Instructions (1-6) are populated and aligned with principles.
- Metadata (Level, Tags, Categories, Stack, Delegates To, Escalates To, Reports To, API Config) is validated and updated.
- Potential `.roo/context/` needs are identified.
- Task status is updated to Complete ✅ upon successful review and update.

## Checklist
- [x] Read the entire mode file (`read_file 03x-worker/039-cross-functional/eslint-specialist/039-work-xf-eslint-specialist.mode.md`).
- [x] Verify/Assign standard emoji in `name` field.
- [x] Ensure standard sections are present (add placeholders if needed).
- [x] Review/Update Description.
- [x] Review/Update Capabilities.
- [x] Review/Update Workflow.
- [x] Review/Update Role Definition.
- [x] Review/Update Custom Instructions (Sections 1-6).
- [x] Validate/Update Metadata: Level.
- [x] Validate/Update Metadata: Tags.
- [x] Validate/Update Metadata: Categories.
- [x] Validate/Update Metadata: Stack.
- [x] Validate/Update Metadata: Delegates To (based on full v7 mode set).
- [x] Validate/Update Metadata: Escalates To (based on full v7 mode set).
- [x] Validate/Update Metadata: Reports To (based on full v7 mode set).
- [x] Standardize Metadata: API Configuration (default: `gemini-2.5-pro`).
- [x] Identify potential `.roo/context/eslint-specialist/` needs.
- [x] Apply changes to the mode file (using `apply_diff` or `write_to_file`).
- [x] Mark task as complete. 📣

## Notes
*   Reference `v7.0/future-planning/current-status-and-mode-refinement-plan.md` for detailed scope.
*   Reference `v7.0/templates/mode_template.md` for section structure.
*   Reference `v7.0/templates/mode_hierarchy.md` for reporting/delegation structure.
*   Reference `v7.0/future-planning/mode-manifest-org-chart.md` (draft) for context.

## Changes Made
1. Updated the Level from "032-worker-tooling" to "039-worker-cross-functional" to align with the mode hierarchy.
2. Updated Escalates To list to include `frontend-lead` instead of `senior-developer` to align with the mode hierarchy.
3. Updated Reports To list to include `frontend-lead` to align with the mode hierarchy.
4. Identified potential `.roo/context/eslint-specialist/` needs:
   - ESLint configuration templates
   - Common rule sets for different frameworks
   - Performance optimization guidelines
   - Migration guides from legacy to flat config
   - Plugin compatibility matrices

## Potential `.roo/context/` Needs
The ESLint Specialist mode would benefit from the following context files:
- `.roo/context/eslint-specialist/config-templates/` - Directory containing various ESLint configuration templates for different project types
- `.roo/context/eslint-specialist/rule-sets/` - Common rule sets for different frameworks (React, Vue, Angular, etc.)
- `.roo/context/eslint-specialist/performance-guidelines.md` - Best practices for optimizing ESLint performance
- `.roo/context/eslint-specialist/migration-guides/` - Guides for migrating from legacy to flat config
- `.roo/context/eslint-specialist/plugin-compatibility.md` - Compatibility matrix for popular ESLint plugins