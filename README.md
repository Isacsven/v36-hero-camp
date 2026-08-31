# CSS-arv
CSS-arv innebär att vissa egenskaper som t.ex. typsnitt och textfärg "rinner ner" (ärvs) av barn elementen/taggarna. Vilket innebär att så länge ett barn element inte satt en egen textfärg, använder den textfärgen från den första föräldren som satt en färg. Fördelen med det här är att man bara behöver skriva en CSS-regel istället för en för varje barn.

## Exempel
Header-taggen med klassen hero har barnen h1, och tre p-taggar (.datum, .plats och .tagline). Även fast typsnittet och textfärgen endast är stilad på hero klassen, så ärver alla barnen dessa egenskaper. Backgrundsfärgen och padding ärvs dock inte utan stannar på föräldern (Box Model ärvs inte).