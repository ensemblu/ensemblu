![Ensemblu Ecosystem Banner](https://raw.githubusercontent.com/ensemblu-corp/assets/main/images/github-cover.png)

# Ensemblu Ecosystem (`com.ensemblu`)

<p align="center">
  <img src="https://raw.githubusercontent.com/ensemblu-corp/assets/main/images/logo-icon.png" alt="Ensemblu Logo" width="100" />
</p>

<p align="center">
  <em>Immutable data-oriented infrastructure for modern Java. Zero reflection magic, zero dependency bloat, zero framework control flow.</em>
</p>

<p align="center">
  🌐 <strong><a href="https://ensemblu-corp.github.io/assets/index.html">Project Axiom Homepage</a></strong>
</p>

---

## Published Packages (Sonatype Central)

### [axiom](https://github.com/ensemblu-corp/axiom)

* **Description:** The sovereign, zero-dependency foundation for structural governance and persistent data-oriented architecture.
* **Version:** `2.0.0`
* **License:** Limited Commercial License

### [axiom-sovereign](https://github.com/ensemblu-corp/axiom-sovereign)

* **Description:** High-performance, byte-native structural parser — the assembly line that turns raw streams into immutable `PersistentMap` structures.
* **Version:** `2.0.0`
* **License:** Limited Commercial License

### [axiom-language](https://github.com/ensemblu-corp/axiom-language)

* **Description:** Grammar, schema policies, and `SchemaGuard` — perimeter validation against `.axiom` schemas.
* **Version:** `2.0.0`
* **License:** Limited Commercial License

### [axiom-spec](https://github.com/ensemblu-corp/axiom-spec)

* **Description:** CSV / JSON / SQL parsers, `JsonEmitter`, database contracts (`AxiomProtocol`), and materializers.
* **Version:** `2.0.0`
* **License:** Limited Commercial License

### [axiom-warp-jdbc](https://github.com/ensemblu-corp/axiom-warp-jdbc)

* **Description:** Zero-reflection JDBC execution engine — strikes, bulk ingest, parallel scopes, explicit contracts.
* **Version:** `2.0.0`
* **License:** Limited Commercial License

### [axiom-warp-reactive](https://github.com/ensemblu-corp/axiom-warp-reactive)

* **Description:** Non-blocking counterpart on Vert.x 5 — same contract as JDBC, `Future<Result<T>>`, backpressure-aware ingest.
* **Version:** `2.0.0`
* **License:** Limited Commercial License

---

## Reference Demonstration

### [axiom-strike-jdbc](https://github.com/ensemblu-corp/axiom-strike-jdbc)

* **Description:** Flagship reference implementation — bare `HttpServer`, `SchemaGuard`, dynamic / bulk / parallel strikes against PostgreSQL. No Spring, no ORM.

---

## Technical Articles & Architecture Notes

<p align="center">
  📚 <strong><a href="https://github.com/ensemblu-corp/assets/blob/main/blogs">Technical Articles & Architecture Notes</a></strong>
</p>

Explore the design, philosophy, and engineering decisions behind the Ensemblu ecosystem:

### [Axiom Type Bridging Guide](https://github.com/ensemblu-corp/assets/blob/main/blogs/axiom-type-bridging-guide.md)

* **Description:** How Axiom avoids heavy ORM type registries — PostgreSQL coercion families, primitive carriers, and explicit inline `::cast` boundaries. When you must cast, and when you must not.

### [Axiom vs. The Java Persistence Landscape](https://github.com/ensemblu-corp/assets/blob/main/blogs/axiom-vs-java-persistence-landscape.md)

* **Description:** Head-to-head architectural contrast — Axiom’s zero-reflection pipeline against Hibernate, EclipseLink, Spring Data, jOOQ, Querydsl, MyBatis, Spring JDBC, and JDBI.

### [Axiom 1.0.0 → 2.0.0 — Ultimate Release Changelog](https://github.com/ensemblu-corp/assets/blob/main/blogs/changelog-1.0.0-to-2.0.0.md)

* **Description:** Full breaking-change map for the major release: `String` → `byte[]` parsers, `Dop` as final utility, removal of `Dop.toJson` in favour of `JsonEmitter`, Vert.x 5.1.6, migration checklist, and cross-module impact.

### [Hard Truths About Java Persistence](https://github.com/ensemblu-corp/assets/blob/main/blogs/axiom-persistence-hard-truths.md)

* **Description:** Eight critical statements — entity-per-table packaging theatre, one-screen-one-query, type-safety without becoming jOOQ/Hibernate, dynamic query as the real topic, production pain from not understanding SQL, ORM popularity as postponed learning, SQL-centric philosophy before NoSQL, and aiming to be an expert at writing SQL.
