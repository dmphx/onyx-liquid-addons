# Onyx Liquid Home Assistant Add-on

This add-on serves the Onyx Liquid dashboard through Home Assistant Ingress.

[![Add the Onyx Liquid repository to Home Assistant](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Fdmphx%2Fonyx-liquid-addons)

This repository contains only public add-on metadata. The prebuilt application
image remains in a private Gitea package registry; an authorized Home Assistant
Supervisor registry credential is required to install or update it. No
application source, build context, or private configuration is published here.

## Configuration

- `hass_url`: Optional Home Assistant URL to prefill at runtime
- `token`: Optional long-lived access token to prefill at runtime
- `dashboard_config_url`: Optional Navet dashboard YAML export to import on first launch in a fresh browser

If connection values are not provided, Navet falls back to manual setup in the UI.
Home Assistant credentials entered in one browser and dashboard layout changes are saved to the
add-on data directory and shared with other browsers that open the same Navet instance.
