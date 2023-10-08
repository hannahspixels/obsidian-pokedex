# obsidian-pokedex

A collection of files for use with the application [Obsidian.md](https://obsidian.md/) as a Pokédex which can display relations between Pokémon in a highly interactive and visual manner. These files may also be integrated into a personal vault to add a quick and easy way to reference any Pokémon within Obsidian.

- This Pokédex covers numbers 1-1016.
- Attributes implemented include:
	- `aliases`
		- Mega and Primal Pokémon have `Mega [name]` and `Primal [name]` aliases.
		- Every regional Pokémon has the region-less name as an alias (e.g. `Kantonian Raichu` has a `Raichu` alias).
		- Pokémon with alternate forms have an alias that would be more easily spoken (e.g. `Deoxys (Speed Forme))` has a `Speed Forme Deoxys` alias)
	- `type`
		- Primary and secondary types.
	- `mega-type`
		- Some Mega Pokémon have alternate types, so the Mega evolution's type is recorded separately.
	- `GO type boost`
		- Primal Kyogre, Primal Groudon, and Mega Rayquaza boost types in Pokémon GO that are in-line with weather boosts rather than their own types—this attribute records those.
	- `national dex number`
	- `tags`
		- Origin-region tags, and tags to mark Megas, Gigantamax, and regional form Pokémon.
	- `evolution line`
		- Links to each other Pokémon in the evolution line.
	- `associated`
		- Links to regional forms and alternate forms of that Pokémon.

