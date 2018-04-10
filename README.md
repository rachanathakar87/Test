# Query Redirector - Chrome extension

## SYNOPSIS

The extension helps in redirecting to customer accounts as super_admin. It's a simple interface to put a command id
and then a new tab is opened with the qubole environmen.

## Features

1. Configurable qubole environments
2. Auto redirect to customer's account based on query id

## Limitations

1. If the user is already logged in to the Qubole environment the redirector won't log him out user will have to manually log off

## Roadmap

Core functionality features takes priority over the UI.

### Core Functionality

1. Add the tracking of active environment and a auto logout feature once user tries to redirect in an active environment
2. Add capabilities to redirect into accounts directly if we have an account ID
3. Add capabilitles to view queries without redirecting

### UI Improvements

1. Add a qubole logo in the background
# Test
