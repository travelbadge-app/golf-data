# US golf courses

`golf-courses.json`: 14,509 US golf courses as `[id, name, state, city, latitude, longitude, par]`
(par is 0 where unknown).

It is a trimmed, tidied extract of the **OpenGolfAPI US golf courses** dataset
(https://github.com/opengolfapi/data), which is built on **OpenStreetMap** data.

- **Changes made:** only those fields were kept; records for the same course (same name, city and state, within
  about 2 km) were merged; a few name quirks were tidied ("Oaks Golf Club The" became "The Oaks Golf Club",
  stray "tm" marks were removed, "Black At Bethpage State Park Golf Course" became
  "Bethpage State Park Golf Course (Black)"). The `id` is the first 8 characters of OpenGolfAPI's id.
- **License:** Open Database License (ODbL) 1.0: https://opendatacommons.org/licenses/odbl/1-0/
  You may use, share and adapt it, including commercially, as long as you credit it and keep any database you
  build from it under the same license.
- **Credit:** © OpenStreetMap contributors (ODbL 1.0) via OpenGolfAPI
