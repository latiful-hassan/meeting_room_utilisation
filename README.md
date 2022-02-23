# overcrowded_office
**Context**

- A law firm has an issue with staff claiming meeting rooms are never availiable to book, however, the partners suspect that the issue is down to poor utilisation of the spaces, as some are book but never used - therefore, they do not know if they should expand the office

**Task**

- With the existing floor plans, create a polygon map to visualise utilisation vs actual utilisation

Techniques & Process**

- Connect to *meeting_rooms* and **Inner Join** *Rooms* to *Room Shapes*:

![](https://github.com/latiful-hassan/overcrowded_office/blob/main/overcrowded_office_screenshots/rooms_join.png)

- Created a polygon map to show the room layouts for first and ground floor (selectable via filter):

![](https://github.com/latiful-hassan/overcrowded_office/blob/main/overcrowded_office_screenshots/initial_polygon_map.png)

- Overlayed the polygon map on the floor plan:

![](https://github.com/latiful-hassan/overcrowded_office/blob/main/overcrowded_office_screenshots/floor_plan_polygon_map.png)

- Blended the data with *meeting_rooms_utilisation*
- Adding *Booked Utilisation* into the colour shelf:

![](https://github.com/latiful-hassan/overcrowded_office/blob/main/overcrowded_office_screenshots/floor_plan_polygon_map_booked_utilisation.png)#

-

**Analysis & Insights**

-
