
import json
from pprint import pprint
with open('TPBL.json') as json_data:
    parsed_json = json.load(json_data)


if (parsed_json["league"]["players"]["born"]["year"]) >= 1998:
    team = (parsed_json["tid"])

if team == 29:
    print(parsed_json["value"])
