# Pioneer — desktop releases

Dette repository indeholder **kun udgivne artefakter** til Pioneer desktop-klienten:
installere til macOS og Windows, og de feed-filer (`latest.yml`, `latest-mac.yml`)
som appens indbyggede opdateringsfunktion læser.

**Der er ingen kildekode her, og der kommer ingen.** Pioneers kildekode ligger i et
privat repository. Dette repository er offentligt af én grund: appens opdateringsfeed
skal kunne læses uden en adgangsnøgle. Alternativet ville være at lægge et GitHub-token
ind i hver installeret app, hvor enhver med appen kan læse det.

## Til dig der er faldet over det her

Installerne er frit downloadbare, men appen kan ikke bruges uden en Pioneer-konto.

## Til Pioneer-udviklere

Releases oprettes af `desktop-release.yml` i hovedrepositoriet. Udgiv aldrig herfra
i hånden: en release der lander her, hentes af hver installeret klient, og der er
ingen fortrydelsesknap. Se `docs/runbooks/desktop-auto-update.md`.
