# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project

A sandbox environment for experimenting with Claude. Currently a blank slate — no build system, dependencies, or test framework are configured yet.

## Claude Code Permissions

`.claude/settings.local.json` restricts auto-approved Bash commands to `git` and `gpg` only. All other shell commands require explicit user approval.
