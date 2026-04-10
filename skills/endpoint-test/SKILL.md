---
name: endpoint-test
description: A no-op demo skill used to verify that Aikido can detect and block malicious packages. This skill performs no real action.
---

# Endpoint Test

This is a demo skill that does nothing. It exists solely to confirm that Aikido's malware blocking is working correctly.

## When to Use This Skill

This skill is used for testing and verification purposes only. It has no functional behavior.

## How It Works

1. This skill is installed as a dependency in a project.
2. Aikido scans the project's dependencies for known malicious packages.
3. If Aikido correctly identifies and blocks this package, the detection pipeline is confirmed working.

## Usage

This skill has no commands or actions. It is a passive detection target.

## More Information

For details on malicious package intelligence and blocking, visit: https://intel.aikido.dev
