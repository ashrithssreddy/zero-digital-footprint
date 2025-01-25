# Privacy-Focused Search Engines

## Introduction
Search engines are often a significant source of data collection, tracking, and profiling. Privacy-focused search engines eliminate tracking, reduce data retention, and serve unbiased results. For those seeking stronger anonymity, advanced methods like self-hosting or decentralized systems are essential.

---

## Privacy-Focused Search Engines
### 1. [DuckDuckGo](https://duckduckgo.com/)
- Does not track searches or store personal data.
- Uses ads based on search keywords but without profiling users.
- Provides integrations with browsers and mobile apps.

### 2. [Startpage](https://www.startpage.com/)
- Serves Google search results without tracking or logging user data.
- Based in the Netherlands, ensuring adherence to strong privacy laws.
- Offers a "view anonymously" feature to open links in a proxy for additional privacy.

### 3. [Qwant](https://www.qwant.com/)
- A European search engine that does not collect personal data.
- Provides categorized search results (web, news, social).
- Adheres to GDPR standards and avoids behavioral profiling.

### 4. [Brave Search](https://search.brave.com/)
- A search engine by the makers of the Brave browser.
- No tracking or profiling of users.
- Offers a fully independent search index and integrates well with the Brave ecosystem.

### 5. [Mojeek](https://www.mojeek.com/)
- An independent search engine with its own indexing infrastructure.
- Does not track users or personalize results.
- Prioritizes neutrality in search results.

### 6. [Searx](https://searx.space/)
- A decentralized metasearch engine.
- Can be self-hosted for maximum control and customization.
- Aggregates results from multiple search engines without exposing user data.

---

## Advanced Practices for Search Engine Privacy

### 1. **Self-Host a Searx Instance**
- Set up a private [Searx](https://searx.space/) instance to avoid relying on public nodes.
- Provides full control over configuration and ensures queries are not logged.
- Recommended to route the instance through Tor or VPN for additional anonymity.

---

### 2. **Use a Tor-Based Metasearch System**
- For maximum anonymity, run searches through:
  - **DuckDuckGo’s Tor onion service**: `https://duckduckgogg42xjoc72x3sjasowoarfbgcmvfimaftt6twagswzczad.onion/`.
  - Public **Searx instances** over Tor for decentralized, anonymized queries.

#### Note:
- Tor exit nodes are publicly monitored. Combine Tor with a no-log VPN for additional security.

---

### 3. **Decentralized Search with YaCy**
- [YaCy](https://yacy.net/) operates as a peer-to-peer search engine where users act as nodes in a decentralized network.
- Ensures no single entity controls or tracks search data.
- Challenges:
  - Requires technical setup and node maintenance.
  - May provide slower or less accurate results for niche queries.

---

### 4. **Harden DNS for Search Queries**
- Use encrypted DNS protocols like **DNS over HTTPS (DoH)** or **DNS over TLS (DoT)** to prevent metadata leaks.
- Recommended resolvers:
  - **Quad9**: Blocks malicious domains while preserving privacy.
  - **Mullvad DNS**: Privacy-focused DNS for anonymity.
  - **DNSCrypt**: Customizable, self-hostable encrypted DNS service.

#### Implementation:
- Harden DNS settings at the router or OS level.
- Combine with a firewall to block unencrypted DNS queries.

---

### 5. **Browser Isolation for Search**
- Use isolated browser environments to prevent cross-contamination of search behavior:
  - **LibreWolf** or hardened Firefox with privacy-focused extensions.
  - Utilize **Firefox Multi-Account Containers** to sandbox search-related activities.
  - For maximum isolation, run searches inside virtual machines using **Qubes OS** or **Whonix**.

---

### 6. **Avoid All Third-Party Engines**
- Even privacy-respecting engines like DuckDuckGo may rely on centralized services (e.g., Bing or Google).
- Alternatives:
  - Use **CrawlBot scripts** or APIs to scrape web data directly.
  - Build custom scrapers on hardened servers to avoid reliance on external engines.

---

## Fingerprint and Metadata Defense
- Fingerprinting and metadata can reveal browsing patterns even when using private search engines.
- Mitigation:
  1. Regularly rotate browser user agents, screen resolutions, and time zones.
  2. Use hardened browsers with canvas and WebGL fingerprint blocking.
  3. Disable JavaScript or use a script-blocking tool like **NoScript**.

---

## Limitations of Privacy-Focused Search Engines
- Engines relying on third-party services may still have limited independence.
- Decentralized options like YaCy or self-hosted Searx require technical expertise.
- Smaller indexes can lead to less comprehensive search results.

---

## Conclusion
Intermediate solutions like DuckDuckGo or Startpage are sufficient for general privacy needs. For those requiring robust anonymity, advanced tactics like self-hosting Searx, hardened DNS, decentralized search engines, and browser isolation provide enhanced protection. These strategies are essential for users operating in high-risk environments or pursuing complete anonymity.
