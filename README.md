<div align="center">

[![NPM version](https://img.shields.io/npm/v/@glua-addon-types/glua-types.svg?style=flat)](https://www.npmjs.com/package/@glua-addon-types/glua-types)
[![NPM downloads](https://img.shields.io/npm/dm/@glua-addon-types/glua-types.svg?style=flat)](https://www.npmjs.com/package/@glua-addon-types/glua-types) [![Known Vulnerabilities](https://snyk.io/test/github/glua-addon-types/glua-types/badge.svg)](https://snyk.io/test/github/glua-addon-types/glua-types)


</div>

<div align="center">

[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg)](https://conventionalcommits.org) [![js-standard-style](https://img.shields.io/badge/Code%20Style-Standard-brightgreen.svg?style=flat)](http://standardjs.com/) [![Security Responsible
Disclosure](https://img.shields.io/badge/Security-Responsible%20Disclosure-yellow.svg)](https://github.com/nodejs/security-wg/blob/master/processes/responsible_disclosure_template.md)

</div>


# @glua-addon-types/glua-types

Tool to generate typescript definitions for garrysmod.

For use with [Typescript To Lua](https://github.com/Perryvw/TypescriptToLua)

The first run will take a while because all pages need to get fetched from the gmod wiki. Executions after that shouldnt take longer than a couple of seconds.

Caches wiki pages into `./data` and generates declarations in `./typings`

If you want to refresh your cache just delete the `./data` folder and rerun.

to install *just* the typings run

`npm install --save-dev @glua-addon-types/glua-types`
or
`yarn add -D @glua-addon-types/glua-types`

