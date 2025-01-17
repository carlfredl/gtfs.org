# Revision History

**March 12, 2020**

* Updated the `TripDescriptor` description on the GTFS Realtime reference page.

**February 26, 2015**

* Added experimental field `direction_id` to `TripDescriptor` ([discussion](https://groups.google.com/d/msg/gtfs-realtime/b8N2GGd2TBs/0fJ1IOMTjJ0J)).

**January 30, 2015**

* Added Protocol Buffer extension namespace to all remaining GTFS-realtime messages that didn't already have one (such as `FeedMessage` and `FeedEntity`).

**January 28, 2015**

* Added experimental field `delay` to `TripUpdate` ([discussion](https://groups.google.com/forum/#!topic/gtfs-realtime/NsTIRQdMNN8)).

**January 16, 2015**

* Update description of `TripDescriptor.start_time`.

**January 8, 2015**

* Defined experimental enum `OccupancyStatus`.
* Added experimental field `occupancy_status` to `VehiclePosition` ([discussion](https://groups.google.com/forum/#!topic/gtfs-realtime/_HtNTGp5LxM)).

**May 22, 2014**

* Updated description of `ScheduleRelationship` enum in `StopTimeUpdate` message ([discussion](https://groups.google.com/forum/#!topic/gtfs-realtime/77c3WZrGBnI)).
* Removed REPLACEMENT from `ScheduleRelationship` enum values in `TripDescriptor` message ([discussion](https://groups.google.com/forum/#!topic/gtfs-realtime/77c3WZrGBnI)).

**Oct 12, 2012**

* Added timestamp field to `TripUpdate` message.

**May 30, 2012**

* Added specific details about Extensions to the specification.

**November 30, 2011**

* Added Protocol Buffer extension namespace to key GTFS-realtime messages to facilitate writing extensions to the spec.

**October 25, 2011**

* Updated documentation to clarify that `alert`, `header_text` and `description_text` are both plain-text values.

**August 20, 2011**

* Updated documentation to clarify semantics of the `TimeRange` message.

**August 22, 2011**

* Initial version.