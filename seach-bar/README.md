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

## Requerimientos

### Mobile
Todo el searchbar debe ser clickable para abrir el modal de filtro de ciudad (es decir no solo el botón de search), esto también aplica para el search bar del navbar 

![image](https://user-images.githubusercontent.com/72823833/115590950-d060e980-a28e-11eb-94f4-5d89eea25edc.png)

Los botones del modal para volver y cerrar deben funcionar correctamente

![image](https://user-images.githubusercontent.com/72823833/115590999-db1b7e80-a28e-11eb-822a-3e6c8c790b08.png)

Se debe de recordar las opciones previamente seleccionadas en caso de que el usuario cierre el modal

El filtro de fechas no debe ser obligatorio

### Tablet
El comportamiento debe ser identico al de mobile

### Desktop
El botón de search se debe expandir cuando un elemento del search bar tiene focus

![image](https://user-images.githubusercontent.com/72823833/115599923-5da93b80-a299-11eb-85ca-e5becb966045.png)
![image](https://user-images.githubusercontent.com/72823833/115599897-55510080-a299-11eb-85c7-700e15c1b182.png)

Cada vez que se selecciona una filtro, se debe abrir el siguiente.

![chrome-capture](https://user-images.githubusercontent.com/72823833/115600262-be387880-a299-11eb-9778-ff880ad40a42.gif)

El botón de neighborhood debe estár deshabilitado si no se ha seleccionado una ciudad.

![image](https://user-images.githubusercontent.com/72823833/115600365-db6d4700-a299-11eb-966f-47c8e75bbcf9.png)

Si se presiona buscar y no se ha seleccionado una ciudad, se debe abrir el dropdown de ciudad.

![chrome-capture (1)](https://user-images.githubusercontent.com/72823833/115601365-f1c7d280-a29a-11eb-98a8-ab91dcb5b10b.gif)


### General (Mobile, tablet y desktop)
El logo de casai debe estar alineado con el searchbar y con el copy.

![image](https://user-images.githubusercontent.com/72823833/115591047-e9699a80-a28e-11eb-8914-c888380980d3.png)

El searchbar se tiene que mostrar en el navbar en las siguientes páginas:

## Páginas en donde mostrar el search bar

- About us
- Edit profile
- manage stay
- my stays
- update password
- lease to casai
- error page
- not found
- Home
En las otras páginas se debe mostrar el navbar normal, es decir sin el searchbar

Para obtener las ciudades y las colonias se hace un request, si este request falla, en lugar de mostrar el search bar se va a mostrar el botón de See apartments

![image](https://user-images.githubusercontent.com/72823833/115604583-c646e700-a29e-11eb-9e9d-2f6595ce65ad.png)

