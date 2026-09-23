https://gerardfp.github.io/calendar/

# Calendar

A simple, printable, single-page year calendar. It automatically fits on a single sheet of paper of any size.

## Usage

Simply open `index.html` in your browser. You can customize the view using the following URL parameters.

### Parameters

| Parameter | Format | Description |
| :--- | :--- | :--- |
| `year` | `YYYY` | Specifies the year (e.g., `?year=2025`). Default is the current year. |
| `start_month` | `YYYY-MM` | The starting month for a custom 12-month range (e.g., `?start_month=2024-09`). |
| `end_month` | `YYYY-MM` | The ending month for a custom range (e.g., `?end_month=2025-06`). Note: The calendar is capped at 12 months. |
| `layout` | `string` | Use `?layout=aligned-weekdays` to align months so that the same weekdays appear on the same rows across the year. |
| `sofshavua` | `flag` | If present (`?sofshavua`), shifts the weekend shading to **Friday and Saturday**. Default is Saturday and Sunday. |

## Printing Tips

- Use **Landscape** orientation.
- Disable **Headers and Footers** in your browser's print settings.
- Ensure **Background Graphics** (or "Color") is enabled to see the weekend shading.

---
Original concept by [Neatnik](https://source.tube/neatnik/calendar).
