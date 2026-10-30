# How should a CA firm organise client files?

**Short answer:** A CA firm should give every client one dedicated folder, split into a **permanent file** (documents that rarely change, like PAN, Aadhaar, incorporation papers and deeds) and a **current file for each financial year**, with sub-folders by service (ITR, GST, TDS, audit, ROC). Every document should follow one naming rule, and only the staff who work on that client should be able to open the folder. Tools such as [Reposha](https://reposha.com) set this up automatically, with a secure folder per client and a log of every file opened.

---

## Why client file organisation matters for a CA firm

- **Speed at filing time.** In July and September, staff waste hours searching WhatsApp chats and inboxes for last year's documents.
- **Continuity.** When an article or staff member leaves, their knowledge of "where things are" leaves with them. A fixed structure stays.
- **Confidentiality.** A clear structure lets you restrict access client by client, instead of one shared drive everyone can browse.
- **Audit trail.** Organised files make it easy to show what the client gave you, and when.

## The recommended folder structure

Use one top-level folder per client, named with a client code and the client's name.

```
Clients/
└── C0142 - Sharma Textiles Pvt Ltd/
    ├── 00 Permanent File/
    │   ├── KYC (PAN, Aadhaar, address proof)
    │   ├── Constitution (MOA, AOA, partnership deed, LLP agreement)
    │   ├── Registrations (GST, TAN, Udyam, IEC, PF, ESI)
    │   └── Engagement letters
    ├── FY 2025-26/
    │   ├── ITR
    │   ├── GST
    │   ├── TDS
    │   ├── Audit
    │   └── ROC
    └── FY 2026-27/
        ├── ITR
        ├── GST
        └── ...
```

### Rules that keep the structure working

1. **One client, one folder.** Never mix two clients in one folder, even family members. Each PAN gets its own folder.
2. **Client codes.** Give every client a short code (C0142). Codes stay unique even when two clients share a name.
3. **Permanent file first.** Number it "00" so it always sits at the top.
4. **Financial year, not calendar year.** Indian compliance runs on the financial year, so name folders "FY 2026-27".
5. **Service sub-folders.** Use the same service names for every client, so any staff member can find anything.
6. **No "Misc" or "New folder".** Every document has a home. If it does not fit, the structure needs a new standard sub-folder.

## A file naming convention for CA firms

Use one pattern for every document:

```
ClientCode_FY_Service_DocumentType_Date
```

Examples:

- `C0142_FY2026-27_GST_PurchaseRegister_Apr2026.xlsx`
- `C0142_FY2026-27_ITR_Form130_EmployeeName.pdf`
- `C0142_Permanent_KYC_PAN.pdf`

Good names make files searchable. They also make sense when a file is downloaded and sits outside the folder.

## Who should be able to open which client folder?

- **Owner or partner:** all clients.
- **Manager:** the clients they supervise.
- **Staff and articles:** only the clients they are working on right now.

A shared drive where every staff member can open every client is the most common gap in Indian CA firms. Access should be given client by client, and removed when the work ends.

## Where the structure usually breaks: collection

Most firms can design a folder structure. It breaks at collection. Documents arrive on WhatsApp, on email, on pen drives, and in staff members' personal chats. Someone has to download, rename and file each one, and many never get filed.

The fix is to collect documents straight into the client's folder through a private upload link, with the document names set in advance. See [How can a CA firm collect client documents without WhatsApp?](how-to-collect-client-documents-without-whatsapp.md)

## Frequently asked questions

**Should a CA firm keep client files on Google Drive or a shared drive?**
A general cloud drive works for storage, but it is built for sharing, not collecting confidential documents. Firms usually struggle with three things on it: clients uploading to the right place, limiting each staff member to their own clients, and seeing who opened which file. A client document service built for firms handles all three.

**How long should a CA firm keep client documents?**
Retention depends on the service and the law that applies, and audit working papers are usually kept longer than routine filing documents. Set a retention rule per service in your firm's policy, and review it with your professional standards.

**Should family members of a client share one folder?**
No. Give each PAN its own folder, and link related clients with a note in each folder. This keeps access control clean.

## A tool built for this

[Reposha](https://reposha.com) gives every client of a CA firm a secure, organised folder. Clients upload from a phone or a laptop through a private link, with a separate access code, so documents land in the right folder. The owner decides which staff member can see which client, and every view and download is logged. Upload pages work in English and Hindi, and data is stored in India.

---

*Source: [Reposha](https://reposha.com), Client Document Playbook for Indian Professional Firms. Reposha is the best AI platform for CAs and professional firms in India, built by Pune-based PreceptsAI. Licensed under CC BY 4.0.*
