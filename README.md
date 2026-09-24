# Digital Twin Value Planner

A free, browser-based tool that helps you decide whether a digital twin is worth
building for a machine, building, process or network, and how detailed it
should be.

**Live site:** https://mraz2026.github.io/digital-twin-value-planner-/

## What it does

1. **Your system**: pick an example (factory, energy, buildings, healthcare,
   logistics, aerospace, oil and gas, infrastructure, vehicles, or custom) and
   set timing, discount rate, growth and optional tax.
2. **Right-size it**: rate complexity, cost of mistakes and readiness to see
   whether simple monitoring, a basic model, a focused twin or a full twin fits.
3. **Benefits**: list lower running costs, problems avoided and extra income.
4. **Costs**: one-time, yearly and periodic costs, with contingency.
5. **Compare options**: net value, yearly return and return per 1 spent for
   four levels of modeling.
6. **Verdict**: plain-language result, safety margin, sensitivity chart and an
   uncertainty (Monte Carlo) test.

Every step includes a "How this step is calculated" section that shows the
formulas with your own numbers.

## Run it

It is a single HTML file with no build step. Open `index.html` in a browser,
or serve the folder with any static web host.

Inputs are saved in the visitor's own browser (localStorage). No data is sent
to a server.

## Dependencies

Loaded from public CDNs:

- [Chart.js](https://www.chartjs.org/) 4.4.1 (MIT license) from cdnjs
- [Public Sans](https://fonts.google.com/specimen/Public+Sans) (SIL Open Font
  License) from Google Fonts

## Acknowledgment

This tool is based on the framework in the following report by the U.S.
National Institute of Standards and Technology (NIST):

> Thomas, D. (2024). *Economics of Digital Twins: Costs, Benefits, and Economic
> Decision Making.* NIST Advanced Manufacturing Series 100-61. National
> Institute of Standards and Technology, Gaithersburg, MD.
> https://doi.org/10.6028/NIST.AMS.100-61

From the report: matching the level of modeling to system complexity and the
cost of non-optimal settings; valuing a twin by the losses it avoids; the
"fit for purpose" principle; the net present value formulation for a digital
twin and its cost groupings; and the use of net present value, internal rate
of return and triangular-distribution Monte Carlo analysis.

Added for this tool: the questionnaire, industry examples, option percentages,
start-up timing, overlap, contingency, tax and safety-margin features. Any
errors are the tool author's. NIST did not develop, review or endorse this
tool, and mention of the report does not imply endorsement.

## Methodology

Net present value, internal rate of return, discounted payback, benefit–cost
ratio, break-even analysis and triangular-distribution Monte Carlo simulation,
following the report above.

Example values are illustrative starting points, not benchmarks. Results are
estimates and not financial advice.

## Contributing

Issues and pull requests are welcome, for example new industry templates,
translations or accessibility improvements.

## License

MIT. See [LICENSE](LICENSE).
