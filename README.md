# ux-calendar-api

Microservicio que devuelve los eventos de UX en Buenos Aires y Alrededores (100km a la redonda)

Este en un Fork del proyecto [calendar-api](https://github.com/meetupjs-ar/calendar-api) de la gente de ## MeetupJS

## Como funciona

* [meetup-api](https://github.com/meetupjs-ar/meetup-api) y [eventbrite-api](https://github.com/meetupjs-ar/eventbrite-api) para obtener eventos de diversas fuentes
* Descarta eventos de días anteriores
* Agrupa por mes y los ordena por fecha

## Desarrollo

```bash
npm install
npm run dev
```

## Licencia

MIT
