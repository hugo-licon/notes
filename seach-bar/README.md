# Search Filter

## Dudas
- ¿Por qué cambia el botón de search?
Cambia cuando está activo

- Los dropdowns tienen la funcionalidad de búsqueda?
No, no tiene.

- ¿Como se visualiza el search bar cuando el campo de ciudad se deja vacio?
Cuando se deja vacio y se presiona se hace un focus al al input de ciudad.

- Cuando se activa la vista de una columna en el calendario
mobile 1 columna
desktop, tablet: 2

hasta 576 que sean dos sino que sea una

- Donde se muestra el search bar del navbar
en todas menos en search y pagos



## Pendientes

- [x] Revisar como se comporta el calendario en distintos idiomas y el formato de las fechas dependiendo el idioma
  - Se va a crear una tarea para solucionar esto.
- [x] Cambiar el margin de las flechas del select
- [ ] Cambiar el height del search bar
- [x] En desktop tiene que ir abriendote los siguientes filtros cada vez que haces click en uno.
- [x] Falta agregar el scroll a las opciones del dropdown
- [x] check loading and error state on searchbar. If we use the go to units button as fallback check the style
- [x] hacer pruebas de performance con y sin lazy loading
- [x] Revisar error en consola sobre export
- [x] Actualizar reset dates label


## Páginas en donde mostrar el search bar
- [x] About us
- [x] Edit profile
- [x] manage stay
- [x] my stays
- [x] update password
- [x] lease to casai
- [x] error page
- [x] not found
- [x] Home


## Issues
Los elementos del navbar en resoluciones con 890px a 1005px width
![6c8000e0.png](:storage/017db0cf-fb28-48bc-852f-62ec10eeae91/6c8000e0.png)


## Keys

|                   Code Key                    |   Screen   |           Section/Title           |      en              |
|-----------------------------------------------|------------|-----------------------------------|----------------------|
| search_bar__city_dropdown_placeholder         | Search Bar | City dropdown placeholder         | Select City          |
| search_bar__neighborhood_dropdown_placeholder | Search Bar | Neighborhood dropdown placeholder | Neighborhood         |
| search_bar__dates_dropdown_placeholder        | Search Bar | Dates dropdown placeholder        | Check In - Check Out |
| search_bar__guests_dropdown_placeholder       | Search Bar | Guests dropdown placeholder       | {{guests} guests     |
| search_bar__guests_counter_text               | Search Bar | Guests counter text               | Guests               |
| search_bar__search_button_text                | Search Bar | Search button text                | Search               |
| search_bar__close_search_bar_button_text      | Search Bar | Close search bar button text      | Close search bar     |
| search_bar__next_button_text                  | Search Bar | Next button text                  | Next                 |
| search_bar__reset_dates_calendar_text         | Search Bar | Calendar reset dates label        | Reset Dates          |
| search_bar__minimum_nights_calendar_text      | Search Bar | Calendar minimum nights Label     | Minimum nights vary  |
| search_bar__small_search_bar_text             | Search Bar | Small search bar text             | Find your next stay  |
