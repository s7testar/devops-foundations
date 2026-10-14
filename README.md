# DevOps Foundations

Hands-on DevOps foundation work covering Linux administration, troubleshooting, networking, permissions, package management, and Git.

## Skills Practiced

- Linux filesystem navigation and permissions
- Process and resource monitoring
- systemd service management
- journalctl and log troubleshooting
- APT package management
- Linux networking and connectivity troubleshooting
- Users, groups, sudo, and service accounts
- Disk, mounts, inode, and storage troubleshooting
- Git and GitHub workflow

## Troubleshooting Approach

Troubleshooting follows a dependency-first workflow: verify the lowest-level layer, identify the failure, apply the fix, and confirm recovery.

Example networking workflow:

1. Check the network interface
2. Check the IP address
3. Check the default route
4. Test the gateway
5. Test Internet connectivity by IP
6. Test DNS resolution
7. Test the application connection

## Next Steps

This repository will continue with practical Git workflows including commits, branches, merges, conflict resolution, GitHub authentication, and remote repositories.

## Git Workflow

Changes are developed on feature branches before being merged into the main branch.

Typical workflow:

1. Create a feature branch
2. Make and test changes
3. Stage the changes
4. Commit the changes
5. Review the branch
6. Merge the feature branch into main

