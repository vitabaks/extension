# tdigest


> [tdigest](https://github.com/tdunning/t-digest): Provides tdigest aggregate function.
>
> https://github.com/tdunning/t-digest





[FUNC](/func) extensions: [`topn`](/topn), [`gzip`](/gzip), [`zstd`](/zstd), [`http`](/http), [`pg_net`](/pg_net), [`pg_smtp_client`](/pg_smtp_client), [`pg_html5_email_address`](/pg_html5_email_address), [`pgsql_tweaks`](/pgsql_tweaks), [`pg_extra_time`](/pg_extra_time), [`timeit`](/timeit), [`count_distinct`](/count_distinct), [`extra_window_functions`](/extra_window_functions), [`first_last_agg`](/first_last_agg), [`tdigest`](/tdigest), [`aggs_for_vecs`](/aggs_for_vecs), [`aggs_for_arrays`](/aggs_for_arrays), [`arraymath`](/arraymath), [`quantile`](/quantile), [`lower_quantile`](/lower_quantile), [`pg_idkit`](/pg_idkit), [`pg_uuidv7`](/pg_uuidv7), [`permuteseq`](/permuteseq), [`pg_hashids`](/pg_hashids), [`sequential_uuids`](/sequential_uuids), [`pg_math`](/pg_math), [`random`](/random), [`base36`](/base36), [`base62`](/base62), [`pg_base58`](/pg_base58), [`floatvec`](/floatvec), [`financial`](/financial), [`pgjwt`](/pgjwt), [`pg_hashlib`](/pg_hashlib), [`shacrypt`](/shacrypt), [`cryptint`](/cryptint), [`pguecc`](/pguecc), [`pgpcre`](/pgpcre), [`icu_ext`](/icu_ext), [`pgqr`](/pgqr), [`envvar`](/envvar), [`pg_protobuf`](/pg_protobuf), [`url_encode`](/url_encode), [`refint`](/refint), [`autoinc`](/autoinc), [`insert_username`](/insert_username), [`moddatetime`](/moddatetime), [`tsm_system_time`](/tsm_system_time), [`dict_xsyn`](/dict_xsyn), [`tsm_system_rows`](/tsm_system_rows), [`tcn`](/tcn), [`uuid-ossp`](/uuid-ossp), [`btree_gist`](/btree_gist), [`btree_gin`](/btree_gin), [`intarray`](/intarray), [`intagg`](/intagg), [`dict_int`](/dict_int), [`unaccent`](/unaccent)


-------
## Extension


| Extension | Version | License | RPM | DEB | PL | `Bin` | `LOAD` | `DYLIB` | `DDL` | `TRUST` | `RELOC` |
|-----------|:-------:|:-------:|:---:|:---:|:--:|:-----:|:------:|:-------:|:-----:|:-------:|:-------:|
| [tdigest](https://github.com/tdunning/t-digest) | 1.4.1 | **<span class="tccyan">Apache-2</span>** | **<span class="tccyan">PGDG</span>** | **<span class="tccyan">PGDG</span>** |  |  |  | <span class="tcblue">✔</span> | <span class="tcblue">✔</span> | <span class="tcwarn">✘</span> | <span class="tcblue">✔</span> |



| Package | Tags | Schemas | Requires | Required by |
|---------|------|---------|----------|-------------|
| [tdigest](/tdigest) |  |  |  |  |





```sql
CREATE EXTENSION tdigest;
```

-----------


## Packages


| OS | Version | License | REPO | Package Pattern | 17 | 16 | 15 | 14 | 13 | 12 | Dependency |
|:--:|---------|:-------:|:----:|-----------------|:--:|:--:|:--:|:--:|:--:|:--:|------------|
| [RPM](/rpm) | 1.4.1 | **<span class="tccyan">Apache-2</span>** | **<span class="tccyan">PGDG</span>** | `tdigest_$v*` | **<span class="tccyan">✔</span>** | **<span class="tccyan">✔</span>** | **<span class="tccyan">✔</span>** | **<span class="tccyan">✔</span>** | **<span class="tccyan">✔</span>** | **<span class="tccyan">✔</span>** |  |
| [DEB](/deb) | 1.4.1 | **<span class="tccyan">Apache-2</span>** | **<span class="tccyan">PGDG</span>** | `postgresql-$v-tdigest` | **<span class="tccyan">✔</span>** | **<span class="tccyan">✔</span>** | **<span class="tccyan">✔</span>** | **<span class="tccyan">✔</span>** | **<span class="tccyan">✔</span>** | **<span class="tccyan">✔</span>** |  |



Install `tdigest` via [Pigsty](https://pigsty.cc/docs/pgext/usage/install/) playbook:

```bash
./pgsql.yml -t pg_extension -e '{"pg_extensions": ["tdigest"]}'
```


Install `tdigest` [RPM](/rpm) from the **<span class="tccyan">PGDG</span>** **YUM** repo:

```bash
dnf install tdigest_17*;
dnf install tdigest_16*;
dnf install tdigest_15*;
dnf install tdigest_14*;
dnf install tdigest_13*;
dnf install tdigest_12*;
```


Install `tdigest` [DEB](/deb) from the **<span class="tccyan">PGDG</span>** **APT** repo:

```bash
apt install postgresql-17-tdigest;
apt install postgresql-16-tdigest;
apt install postgresql-15-tdigest;
apt install postgresql-14-tdigest;
apt install postgresql-13-tdigest;
apt install postgresql-12-tdigest;
```







