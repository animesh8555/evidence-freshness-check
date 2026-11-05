# Freshness examples

All examples here are synthetic.

## Package inspection

A report covers `package.zip` with a recorded digest. The current digest differs. Result: stale; inspect the new package before reusing its security conclusion. The old report remains evidence about the old bytes.

## Commit and configuration

An application check depends on source and `settings.json`. Source is unchanged but settings changed. Recheck the affected behavior. A change to unrelated meeting notes does not automatically invalidate the check, provided those notes were not a dependency.

## Deployment

A local build is verified. The production version cannot be observed. Report local verification and an unverifiable deployment; do not infer the server contains the local artifact.

## Marketplace listing

A listing was free yesterday. A cached screenshot is evidence of yesterday's state, not today's price. Fetch the current authoritative listing before a new action that depends on its current price.
