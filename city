import pyowm

#owm = pyowm.OWM('c597c9de39c3def5391065acc4613824', language = 'ru')
owm = pyowm.OWM('c597c9de39c3def5391065acc4613824', Language = "ru"

#!/usr/bin/python
# '\xd0' coding: <encoding name> '\xd0'
print("В каком городе вы хотите узнать погоду?: ")

#mgr = owm.weather_manager()
#observation = mgr.weather_at_place(place)
observation = owm.weather_at_place(place)

#w = observation.weather
w = observation.get_weather()
#temp = w.temperature('celsius')["temp"]
temp = w.get_temperature('celsius')["temp"]

print(f"В городе {place} сейчас {temp}")      #w.get_detailed_status())
#pri
nt("Температура в городе " + str(temp) )
#print (w)

if temp < 10:
    print("Сейчас холодно. Оденься, как танк!")
elif temp < 20:
    print("Сейчас холодно. Оденься")
else:
    print("Температура шик, одеваемся как суки.")
