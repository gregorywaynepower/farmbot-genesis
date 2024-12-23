---
title: "Picking Up Seeds"
slug: "picking-up-seeds"
description: "The FarmBot fails to pick up seeds entirely, frequently drops seeds when moving, or sucks seeds fully into the needle or vacuum system."
---

# 1. Consider seed characteristics
Seed size, weight, and shape can have considerable impact on the effectiveness and reliability of FarmBot's needle and vacuum pump based seeding mechanism. Seeds should not be excessively small or large, cannot be too heavy, and are ideally of a round, smooth shape. [Pelleted seeds](../reference/seeds.md#pelleted-seeds) are specifically designed for use with farming equipment and are an ideal choice for use with FarmBot. Consult the [seeds page](../reference/seeds.md) for more details.

# 2. Choose the correct needle size
Included with every FarmBot kit are three different luer lock needle sizes that can be easily swapped in and out of the seed injector. This allows you to choose the best needle size for the seeds you are working with. Generally speaking, a larger diameter needle should be used for larger, heavier seeds, while a smaller diameter needle should be used for smaller, lighter seeds. See the [seeds](../reference/seeds.md) page for more details.

If the needle is too small, then the vacuum pump will not be able to create enough suction to consistently and reliably pick up a larger, heavier seed. In some cases, the seed may get picked up but then dropped when FarmBot is moving in the X, Y, and Z directions. In either case, try switching to a larger needle size.

If the needle is too large, then the seeds may accidentally get sucked fully into the needle or vacuum system. If this happens, you will need to remove the seed from the system or else risk total suction loss and malfunction. Once all seeds are removed from the system, switch to a smaller needle size.

# 3. Check the tube for kinks
If the vacuum pump tube is kinked, then airflow will be restricted and suction power at the needle will be significantly diminished. Ensure there are no kinks in the vacuum pump tube. Problematic areas include where the tube transitions from cable carrier to cable carrier (v1.2 kits only).

{%
include callout.html
type="info"
title="Consider relocating the vacuum pump (v1.2 kit owners only)"
content="The v1.2 kit design had the vacuum pump placed on the ground, requiring several meters of tubing between the vacuum pump and the UTM. With v1.3, we relocated the pump to the z-axis, significantly reducing the amount of tubing needed and thereby decreasing the amount of suction power lost due to friction inside the tube. If you have a v1.2 kit, consider [relocating the pump to the z-axis](../upgrades/vacuum-pump-relocation.md) with custom components or [this upgrade kit](https://farm.bot/products/vacuum-pump-v1-2-to-v1-3-upgrade-kit)."
%}

# 4. Check the needle and vacuum system for clogs and contamination
If the needle, seeder, vacuum pump tube, or vacuum pump become clogged with dirt, water, seeds, or other contamination, then the system can lose suction power and cease to function. In some cases, a clogged vacuum pump can actually start *blowing* air instead of sucking it in!

The most likely location for a clog to occur is in the needle. If the needle becomes clogged, first try rinsing it with warm water. If that doesn't work, try inserting a straightened paper clip or other small piece of metal into the needle to dislodge any seeds or other contaminants. If you are unable to remove the clog, you will need to discard the needle and use another one.

The most likely location for contamination to affect the system is inside the vacuum pump. The vacuum pump is a [diaphragm-based pump design](https://en.wikipedia.org/wiki/Diaphragm_pump) that will lose suction power if contaminants such as dirt, water, or seeds, are present on the diaphragm. If you suspect that the vacuum pump is contaminated, remove the four screws holding the two plastic shell components together. Then carefully remove the rubber diaphragm and clean both sides. Reinsert the diaphragm and screw the pump back together.

Using [pelleted seeds](../reference/seeds.md#pelleted-seeds) or other naturally smooth, round shaped seeds can reduce the likelihood of future contamination.

Furthermore, you may consider adding an inline filter to the vacuum tube, such as [this one](https://www.autozone.com/filters-and-pcv/fuel-filter/duralast-fuel-filter/246932_953903_17721) designed for cars.
