# Test Case 2

**Title:** Checking event filtering by event type  
**Priority:** Medium  
**Precondition:** The user is registered on the site and has an active link to the site.

| Step # | Step Action                                    | Data                                                        | Expected Result                                                                                     |
|--------|-----------------------------------------------|------------------------------------------------------------|----------------------------------------------------------------------------------------------------|
| 1      | Follow the link                                | https://www.greencity.cx.ua/#/greenCity/about             | The page is opened                                                                                  |
| 2      | Select Events from the list                    |                                                            | The tab with events is opened                                                                      |
| 3      | Click on the event type                        |                                                            | The tab with event types is opened                                                                 |
| 4      | Select the type -- economic                    |                                                            | Events with the filter "economic" are opened                                                      |
| 5      | Look at the number of events by the filter    |                                                            | It says that 0 events were found --this is a bug                                                   |