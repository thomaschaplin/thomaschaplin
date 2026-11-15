<pre>
$ kubectl describe human thomaschaplin

Name:         thomaschaplin
Namespace:    uk
Labels:       role=systems-engineer
              tinkerer=true
Annotations:  thomaschaplin.me/website: https://www.thomaschaplin.me
API Version:  thomaschaplin.me/v1
Kind:         Human
Spec:
  Role:       Sr. Systems Engineer
  Employer:   Tray.ai
  Location:   Remote, UK
  Focus:      platform engineering, kubernetes, aws
  Languages:  go, typescript, rust, bash
  Tools:      terraform, pulumi, helm, argo cd, grafana, github actions
Status:
  Phase:               Running
  Side Projects:       6   # <a href="#things-ive-made">listed below</a>
  Talks Given:         4   # <a href="https://www.youtube.com/channel/UCgrsESnTqiMw37T-Xh5FW-g">on YouTube</a>
  Merged Upstream PRs: 16  # <a href="contributions.md">contributions.md</a>
  Conditions:
    Type:    Certified
    Status:  True
    Reason:  AWSSolutionsArchitectAssociate  # <a href="https://www.credly.com/badges/6d275756-4a54-470b-93b4-0e7dd6b84f13">Credly badge</a>
Events:
  Type    Reason     Since    Message
  ----    ------     -----    -------
  Normal  Scheduled  2017-08  Joined Algomi as a QA Automation Engineer
  Normal  Pulled     2019-09  Joined Tray.ai as a Software Development Engineer in Test
  Normal  Promoted   2021-11  Software Development Engineer in Test to Sr. Software Development Engineer in Test
  Normal  Migrated   2023-11  Sr. Software Development Engineer in Test to Systems Engineer
  Normal  Promoted   2025-03  Systems Engineer to Sr. Systems Engineer
</pre>

## Things I've made

- 🧾 [Basket Index](https://basketindex.thomaschaplin.me/): your own inflation rate, worked out from your supermarket receipts.
- 🍌 [We Need Bananas](https://weneedbananas.com/): a shared shopping list you join with three words.
- 🔧 [JSON Tools](https://json.thomaschaplin.me/): format, repair, query and diff JSON without it leaving your browser.
- 💀 [kmortem](https://github.com/thomaschaplin/kmortem): a Kubernetes operator that saves a report of what was running on a node, and why it died, before the node is gone.
- 🧵 [rust-counter-strings](https://github.com/thomaschaplin/rust-counter-strings): a CLI that generates counterstrings for testing input fields. Each `*` sits at the position named before it (`2*4*6*8*11*`), so you can see exactly where a field truncates.
- 🍳 [Chaplin Kitchen](https://chaplinkitchen.com/): recipes that actually get cooked.
- 📦 [Many more](https://github.com/thomaschaplin?tab=repositories) on my repositories page.

You can find the rest on [my website](https://www.thomaschaplin.me/), or have a look at my open source [contributions](contributions.md).
