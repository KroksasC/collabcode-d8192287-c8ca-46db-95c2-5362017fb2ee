# dsdasd

A project started together on CollabCode.

## Getting started

Run npm install, then npm run dev.

Commit the package-lock.json produced by npm install.

## Architecture

The frontend keeps application wiring in src/app, feature behavior in src/features, shared UI in src/components, and configured clients in src/lib. Compose features in the app layer; do not import between sibling features.

Starter Issues describe your first milestone.
