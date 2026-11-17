---
title: Binderly Privacy Policy
permalink: /privacy/
---

# Binderly Privacy Policy

**Last updated: November 17, 2026**

Binderly is a desktop application for browsing and managing collectible card collections. This
policy explains what information the app uses, where it goes, and the choices you have.

**In short:** Binderly does not collect your personal information. There are no accounts, no
analytics, no advertising and no crash reporting. Your collection stays on your device. The app
connects to the internet only to download public card data and images.

## Who we are

Binderly is published by **TomasDEV** ("we", "us"). You can contact us at
**privacy@tomaselli.dev** for any question about this policy.

## Information stored on your device

Binderly keeps the following data in a local database and folders inside your user account's
application data folder:

- the card catalog downloaded from the data source (card names, sets, rarities, prices and image
  addresses);
- your collection (which cards you own, with quantity, condition, language and finish);
- your lists, checklists and wishlists (names, colors, icons and tags you choose);
- your preferences (theme, accent color, language, view, filters);
- cached card images.

This data is created by you or downloaded from a public source. **It is not sent to us or to any
other server.** We cannot see it.

If you use the export or backup features, the app writes a file to the location you choose. If you
import or restore a file, the app reads only the file you select. These files stay under your
control; the app never uploads them.

## Information sent over the internet

To work, the app contacts the following services:

- **Scryfall** (`api.scryfall.com` and `cards.scryfall.io`) to download the Magic: The Gathering
  card catalog and card images. As with any web request, Scryfall receives your IP address and
  technical details of the request, including the app's name and version in the User-Agent
  (for example `Binderly/0.1.3 (unofficial desktop collection manager)`). The requests identify
  cards and sets only; they contain none of your collection or list data. Scryfall's own privacy
  practices are described at <https://scryfall.com/docs/privacy>.
- **YGOPRODeck** (`db.ygoprodeck.com` and `images.ygoprodeck.com`), **TCGdex**
  (`api.tcgdex.net` and `assets.tcgdex.net`) and **Lorcast** (`api.lorcast.com` and
  `cards.lorcast.io`), only when you download the catalog of the matching game (Yu-Gi-Oh!,
  Pokémon TCG, Disney Lorcana) and when its card images are shown. The same rules apply as for
  Scryfall: they receive your IP address and the technical details of the request, including the
  app's name and version, and the requests contain only card and set identifiers, never your
  collection or list data. For Pokémon cards, TCGdex is also asked for the price of a card when
  you open its details (the request contains that card's identifier, and the answer is kept on
  your device for a day), so TCGdex can see which Pokémon cards you look at and when. The same
  happens, for a card that exists only in another language, with its type and text.
- **LorcanaJSON** (`lorcanajson.org`) and the official Disney Lorcana card images
  (`api.lorcana.ravensburger.com`), only when you download an extra language (French, German or
  Italian) of the Disney Lorcana catalog and when those images are shown. The same rules apply as
  for the services above.
- **GitHub** (`github.com`), only in the version of Binderly downloaded directly from our website
  or release page, to check whether a newer version is available and to download it. GitHub
  receives your IP address and the usual request details. **The version installed from the
  Microsoft Store does not do this**: updates come only through the Microsoft Store.

Binderly displays its interface using the Microsoft Edge WebView2 runtime, a component of Windows.
Microsoft's own privacy statement applies to that component.

We do not receive any of this traffic. We do not operate servers that your copy of the app talks
to.

## What we do not do

- We do not collect, store or have access to your personal information.
- We do not use analytics, telemetry, tracking, advertising or crash-reporting services.
- We do not sell, rent or share personal information, because we do not have any.
- We do not require an account, and we do not ask for your name, email address, location, contacts
  or payment details.

## Children

Binderly does not knowingly collect information from anyone, including children.

## Keeping or deleting your data

Your data lives only on your device. To remove it, uninstall the app. In the version downloaded
directly, you can also delete the app's data folder in your user account's application data
folder, and clear the image cache from *Settings* inside the app. Backups and exports you created
are ordinary files that you can delete at any time.

## Changes to this policy

If the app changes in a way that affects your privacy (for example, adding online features), we
will update this policy before the change takes effect and change the date at the top.

## Unofficial project

Binderly is an unofficial project. It is not affiliated with, endorsed by or sponsored by the
publishers of any card game. Card names, images and symbols belong to their respective owners.

## Contact

Questions about this policy: **privacy@tomaselli.dev**
