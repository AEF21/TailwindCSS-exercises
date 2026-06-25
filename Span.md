##vad står span för innehåll  i området TailwindCSS10:14Claude responded: Tailwind CSS har inga inbyggda klasser specifikt för <span>-elementets innehåll — men du kan styra vad som visas inuti en span med vanliga utility-klasser.Tailwind CSS har inga inbyggda klasser specifikt för <span>-elementets innehåll — men du kan styra vad som visas inuti en span med vanliga utility-klasser.
Här är de vanligaste kategorierna:
Text & typografi

text-{size} – teckenstorlek (sm, base, lg, xl…)
font-{weight} – fet, tunn osv (bold, semibold, light…)
text-{color} – färg (red-500, gray-700…)
italic, underline, line-through – stil
uppercase, lowercase, capitalize – textomvandling
truncate, text-ellipsis – hantera långa texter

Synlighet & display

hidden – dölj elementet (display: none)
invisible – osynlig men tar plats
inline, inline-block, block – displaytyp
sr-only – synlig bara för skärmläsare

Bakgrund & kant

bg-{color} – bakgrundsfärg
rounded-{size} – rundade hörn
border, border-{color} – kantlinje
px-{n}, py-{n} – padding inuti spannet

Positionering

relative, absolute – position
align-{baseline|top|middle|bottom} – vertikal justering i inline-kontext

Exempel:
html<span class="text-sm font-semibold text-blue-600 bg-blue-100 px-2 py-0.5 rounded-full">
Tagg
</span>