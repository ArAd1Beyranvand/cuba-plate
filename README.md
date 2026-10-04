FREE PALESTINE 🇮🇷🇵🇸 پاینده ایران

GO VEGAN 🌱

==================================

From the mighty people of Iran to the brave people of Cuba to view examples:

https://platexample.ir/#/discover/cuba

# cuba_plate

Cuba's 2013 licence plates for [`plate_core`](https://pub.dev/packages/plate_core).

| Spec | Size (mm) | Format | Notes |
|---|---|---|---|
| `CubaPlates.car` | 420 × 110 | `P 025 245` | Natural persons: white CUBA strip, ruled off |
| `CubaPlates.carLegalEntity` | 420 × 110 | `T 003 526` | Legal entities: blue CUBA strip |
| `CubaPlates.motorcycle` | 200 × 140 | `P` / `28588` | CUBA in a ruled box top-left |

Every plate is black on white, so there is one theme, `CubaThemes.standard`.
`CubaValidator` is advisory: it checks the series letter (I, O, Q, S, W, Z are
not issued) and that the serial fills every cell.

## Sources and accuracy

Measured from the photographs on Wikipedia's *Vehicle registration plates of
Cuba*, each normalised to the documented millimetres. Positions match the
references to within ~2 mm. **The serials are smaller than the real ones:**
car ink is ~66% of reference height and motorcycle ink ~70–76%, because
`plate_core` paints a glyph at about half its slot height and a slot cannot
exceed the canvas. Colours marked `// CALIBRATE` are from photographs.

Not implemented: the 2002–2013 colour-coded series and earlier, and the small
laser-printed control number.

## Also available

- [`plate_core`](https://pub.dev/packages/plate-core) - Paint license plates.
- [`plate_alphabet`](https://pub.dev/packages/plate-alphabet) - A library of alphabets for license plates.
- [`plate_keypad`](https://pub.dev/packages/plate-keypad) - A character picker for license plates.
- [`plate_number_holder`](https://pub.dev/packages/plate-number-holder) - A frame to hold license plate numbers.
- [`algeria_plate`](https://pub.dev/packages/algeria-plate) - Algeria's licence plates.
- [`bolivia_plate`](https://pub.dev/packages/bolivia-plate) - Bolivia's licence plates.
- [`colombia_plate`](https://pub.dev/packages/colombia-plate) - Colombia's licence plates.
- [`germany_plate`](https://pub.dev/packages/germany-plate) - Germany's licence plates.
- [`india_plate`](https://pub.dev/packages/india-plate) - India's licence plates.
- [`indonesia_plate`](https://pub.dev/packages/indonesia-plate) - Indonesia's licence plates.
- [`iran_plate`](https://pub.dev/packages/iran-plate) - Iran's licence plates.
- [`iranshahr_plate`](https://pub.dev/packages/iranshahr-plate) - Iranshahr region's licence plates.
- [`lebanon_plate`](https://pub.dev/packages/lebanon-plate) - Lebanon's licence plates.
- [`malaysia_plate`](https://pub.dev/packages/malaysia-plate) - Malaysia's licence plates.
- [`mali_plate`](https://pub.dev/packages/mali-plate) - Mali's licence plates.
- [`niger_plate`](https://pub.dev/packages/niger-plate) - Niger's licence plates.
- [`palestine_plate`](https://pub.dev/packages/palestine-plate) - Palestine's licence plates.
- [`sudan_plate`](https://pub.dev/packages/sudan-plate) - Sudan's licence plates.
- [`tunisia_plate`](https://pub.dev/packages/tunisia-plate) - Tunisia's licence plates.
- [`venezuela_plate`](https://pub.dev/packages/venezuela-plate) - venezuela_ licence plates.
- [`yemen_plate`](https://pub.dev/packages/yemen-plate) - Yemen's licence plates.
