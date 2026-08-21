<div align="center">

<h1>houssem-plugins</h1>

<p><em>Claude Code plugins by <a href="https://github.com/HoussemDjeghri">Houssem Djeghri</a>.</em></p>

<img alt="license MIT" src="https://img.shields.io/badge/license-MIT-D97757">

</div>

---

## Add the marketplace

```text
/plugin marketplace add HoussemDjeghri/plugins
```

Then install any plugin below. New plugins show up here with
`/plugin marketplace update` — no need to add anything again.

## Plugins

<table>
<tr>
<td width="140" align="center" valign="middle">
  <a href="https://github.com/HoussemDjeghri/bridger">
    <img src="https://raw.githubusercontent.com/HoussemDjeghri/bridger/main/assets/logo.png" width="96" alt="bridger logo"><br>
    <b>bridger</b>
  </a>
</td>
<td valign="top">

**Let two Claude Code sessions talk to each other.** Two independent sessions
message each other through a file-based bus: named peers, immutable per-pair
threads, `ask`/`answer` with full live context, delivery that survives
restarts. No daemon, no runtime — bash + jq.

```text
/plugin install bridger@houssem-plugins
```

Source and docs: https://github.com/HoussemDjeghri/bridger.

</td>
</tr>

<tr>
<td width="140" align="center" valign="middle">
  <a href="https://github.com/HoussemDjeghri/carry-on">
    <b>carry-on</b>
  </a>
</td>
<td valign="top">

**Carry your Claude Code context across sessions.** Save and restore project
context so you can continue work across Claude Code sessions without losing
important state.

```text
/plugin install carry-on@houssem-plugins
```

Source and docs: https://github.com/HoussemDjeghri/carry-on.

</td>
</tr>
</table>

## License

[MIT](LICENSE).
