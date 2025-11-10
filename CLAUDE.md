# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Purpose

This workspace serves as a coordination hub for working across the BlazeBite project ecosystem. BlazeBite provides food ordering apps for small businesses that would otherwise lack the resources to build their own apps.

## BlazeBite Architecture

The BlazeBite platform consists of multiple repositories in the parent directory:

**Customer-Facing Apps:**
- `blazebite-customer-android` - Android customer ordering app
- `blazebite-customer-ios` - iOS customer ordering app
- `blazebite_customer_omni` - Omni-channel customer app
- `blazebite-customer-portal` - Web-based customer portal
- `blazebite-customer-signup` - Customer signup flow

**Kitchen/Operations:**
- `blazebite-kitchen-android` - Android kitchen display/management app

**Admin & Backend:**
- `blazebite-super-admin` - Administrative interface
- `Web-Server` - Backend API server

**Documentation:**
- `blazebite-docs` - Project documentation
- `blazebite-documentation` - Additional documentation

**Storage & Infrastructure:**
- `BlazeBite Storage` - Storage/assets repository

## Workspace Usage

This directory (`blazebite-claude-workspace`) is used for:
- Cross-repository scripts and utilities
- Shared configuration (Esper MDM configs for Android device management)
- Test logs and coordination
- Documentation that spans multiple components
- Environment configuration for development work

When working on specific features or bugs, the actual code changes will typically be made in the respective component repositories, not in this workspace.
