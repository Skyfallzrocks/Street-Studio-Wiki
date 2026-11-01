# Frequently asked questions

## Do I need Road Builder?

No. Street Studio includes its adapted road-generation implementation and uses its own identity and storage. Compatibility with running both generators together is not established by this wiki.

## Do I need Town Road Lane?

No. The manual intersection editor is integrated into Street Studio. Its source credits and license still apply.

## Does every feature work without extra assets?

No. Core editing and optional visual content are separate. Models such as RRFBs, picker islands and parking meters must be loaded before the related features can use them.

## Does this build require a Discord beta key?

The current 0.2.0 mod initialization does not register a beta-key gate. Older private test builds had different access arrangements. Follow the release notes for the build you install.

## Why did editing one road change several streets?

They may share a Street Studio design. Check the editing-scope message and use **Copy design** for an independent layout.

## Can I move refuges?

The current picker instructs you to place a model at the + outline and drag its arrows to adjust its position. The older instruction that all medians/refuges are fixed does not describe this picker workflow.

## Do markings or decorative signs change traffic rules?

Do not assume so. Visual models and painted lines are separate from lane routing, parking access, crossing paths and signal logic.

## Are separately supplied FBX models already installed in Street Studio?

Not automatically. They must be imported, configured and built in the Asset Editor before the game can load their packages. Loading a model also does not guarantee that Street Studio recognizes its asset name.

## Can I remove Street Studio from a city using its roads?

Cities using generated Street Studio roads rely on the mod to reconstruct them. Do not assume disabling or uninstalling it is safe for that save. Keep backups and retain the mod for affected cities until a tested migration path is available.

## Is the roadmap a list of finished features?

No. Proposed UI revisions, more assets and other future plans are not promises that those features exist in the build described here.
