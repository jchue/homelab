# Frigate

Frigate is NVR with real-time AI object detection. It has its own UI but also integrates well with Home Assistant.

## Setup

- The application gets its own external IP using the `macvlan` Docker network driver. The external Docker network must be created as a prerequisite.
- Frigate communicates with Home Assistant via MQTT, so integration requires both services, along with an MQTT broker, to be added to an external `mqtt` Docker network. See the [documentation](https://docs.frigate.video/integrations/home-assistant/) for more details.
