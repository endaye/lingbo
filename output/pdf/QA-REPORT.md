# LINGBO catalog audit, 2026-09-21

## Status

Layout-repaired review set: 10 PDFs, 439 pages. All 10 documents contained an identified issue and were re-exported. This is not approval for technical publication, tool selection or printing. Missing source images and one questionable technical table remain open below.

Only the duplicated working Figma file `DfI02McMiIf6S2Bzvq7VkR`, page `new` (`0:1`), was changed. The locked original Figma file and repository source SVG/CDR assets were preserved. The standalone logo row was excluded.

Page references below are PDF page positions, including cover and contents pages, not the legacy supplier's printed page numbers.

## Repairs made

| Document | Principal repairs |
| --- | --- |
| Gundrill Technical Guide | Restored the 20 mm cylindrical-shank label to its correct position in the ordering diagram. |
| Grooving and Cutting-Off Tools | Removed identified residual Chinese labels and supplier logo fragments; covered obsolete footer/page-number artwork while retaining the LINGBO footer; restored complete English holder-compatibility captions on pages 13 and 15 from the original source. |
| Quick Drills A | Removed identified redundant Chinese captions; removed the old company-photo block; retained and centered the complete CNC machine photo without changing technical illustrations. |
| Quick Drills B | Corrected imported-font wrapping and cumulative row-spacing drift across the toolholder tables; aligned the final technical table above the footer; removed remaining supplier marks; retained original technical strings. |
| Threading Volume 01 | Cleaned identified Chinese labels, redundant captions and supplier-mark remnants; repaired wrapping on pages 36-37. |
| Threading Volume 02 | Cleaned identified Chinese labels and redundant caption fragments, including the ISO full-profile page. |
| Threading Volume 03 | Repaired ordering-code text wrapping on pages 49-50 and cleaned identified Chinese labels, including the final page. |
| Threading Volume 04 | Repaired wrapped/overlapping order codes; reflowed 170 fragments across 32 table rows with a condensed font, preserving the existing characters; cleaned identified source-language remnants. |
| Threading Volume 05 | Cleaned identified Chinese captions and changed the remaining brown raster heading to grayscale. |
| Threading Volume 06 | Cleaned identified Chinese captions; restored complete English insert-type labels on page 9 using the original source SVG as the reference. Retained the existing Volume 06 cover artwork and layout. |

Chinese cleanup on outlined artwork uses background-matched visual masks, with English vector labels where necessary. This is visual cleanup, not secure redaction or removal of every underlying source path. Some original technical text remains outlined/rasterized and therefore is not searchable as normal PDF text.

## Open issues requiring original material or technical approval

### 1. Missing or incomplete illustrations

- Quick Drills A, PDF pages 7 and 8, Figma nodes `28:11945` and `28:11528`: assembly/disassembly steps contain empty illustration areas. The same omissions are visible when independently rendering `svg/快钻 A 2024/快钻A2024-9.svg` and `快钻A2024-10.svg`.
- Quick Drills B, PDF page 6, node `28:54895`: the product photograph is reduced to a narrow fragment. The same defect appears in `svg/快钻 B 2024/快钻B2024-4.svg`.
- Quick Drills B, PDF page 10, node `28:47180`: the product photograph is incomplete. The same defect appears in `svg/快钻 B 2024/快钻B2024-8.svg`.
- Quick Drills B, PDF page 24, node `28:48932`: the dimension illustration lacks its tool body. The same omission appears in `svg/快钻 B 2024/快钻B2024-22.svg`.

These are not caused by the latest PDF export. Complete original PDF/CDR files with embedded images, or the exact missing illustrations, are needed. No similar-looking tool images were substituted and no mechanical diagrams were invented.

### 2. Order-code mapping in Quick Drills B, page 28

Node `28:58266`, the lower imperial table: 14 dimensional records are paired with only 13 order-code entries; a `FQD3/8-25/32-1-12D-CA` entry also needs confirmation in context. Layout has been aligned, but the original strings and dimensions were retained. The supplier/technical owner must confirm the missing entry and row correspondence before this page can be approved for ordering.

## Verification and limits

- Baseline: all 439 pages rendered, contact sheets inspected, and OCR/QR screening run. Detailed views and original SVG renders were used to investigate flagged pages.
- Final structure: all 439 Figma frames retain the expected page size and left-to-right position. Existing LINGBO footer page-number text matches the PDF order.
- Outputs: all 10 PDFs reopened successfully, with expected page counts and uniform A4 portrait MediaBox/CropBox dimensions. No logo-row export or extra blank export pages were added.
- Post-repair verification: 256 changed and representative pages were rendered again at 144 dpi and OCR-screened; all Grooving and Cutting-Off and Quick Drills B pages were included. Contact sheets and enlarged flagged-page views were inspected. Exact page coverage and SHA-256 hashes are recorded in `audit-manifest.json`.
- No QR codes were detected in the baseline or post-repair screening. OCR flags involving diameter symbols, helix-angle symbols, fractions and the address were manually distinguished from actual Chinese text.
- This is a visual/layout audit plus targeted text cleanup, not a line-by-line engineering validation, exhaustive English copy edit, accessibility review, secure-redaction audit, PDF/X preflight, CMYK conversion or physical print proof. Small vector lettering and source punctuation warrant a final human proof before publication.

The English ordering codes, dimensions, units and cutting parameters must be approved by a technically qualified owner. Corrected layout does not certify those values.
