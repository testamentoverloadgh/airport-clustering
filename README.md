## My chosen dataset contains an extensive database of aiprports and landing strips. It has 28,298 entries

The repo can be found [here](https://github.com/mborsetti/airportsdata/tree/main/airportsdata) and the raw csv can be downloaded [here](https://raw.githubusercontent.com/mborsetti/airportsdata/refs/heads/main/airportsdata/airports.csv)

## The features of this dataset are as follows
**icao**: 4-letter indicator

**iata**: 3-letter indicator

**name**: official name

**city**: the city containing the airport

**subd**: subdivision, such as state, province, etc

**country** ISO 3611-1 alpha-2 country code

**elevation**: the MSL elevation of the highest point of the landing area

**lat**: decimal latitude of the airport reference point

**lon**: decimal longitude of hte airport reference point

**tz**: timezone (TZ format)

**lid**: US FAA location identifier

## What real-world problem does this solve
I am looking to use clustering to determine coverage gaps and find good hubs.  For example, a major airline might choose which airports it wants to service in such a way that they don't service two airports within 20 miles of each other.  Additionally, local governments may use this to find areas without airports so they can build some for use by emergency aircraft.  This is an engineering problem because it can be solved programmatically and mathematically.
