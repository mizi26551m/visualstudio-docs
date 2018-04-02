---
title: "Add a Threshold Rule for load testing in Visual Studio | Microsoft Docs"
ms.date: "10/19/2016"
ms.topic: "article"
helpviewer_keywords:
  - "load tests, monitoring"
  - "load tests, thresholds"
  - "load tests, analyzing"
  - "thresholds in load tests"
ms.assetid: 3d8fac8f-426f-4155-9ced-f7cd4c79792c
author: gewarren
ms.author: gewarren
manager: ghogen
ms.technology: vs-ide-test
---
# How to: Add a threshold rule using the load test editor

Threshold rules in load tests compare a performance counter value with either a constant value or another performance counter value.

## To add a threshold rule

1.  Open a load test.

2.  In the Load Test Editor, expand the **Counter Sets** node.

3.  Expand one of the **Counter Categories** in one of the Counter Sets. For example, you can select **LoadTest:Scenario**. Expand the node.

4.  Right-click one of the counters, for example, **User Load**, under **LoadTest:Scenario**. Select **Add Threshold Rule**.

     The **Add Threshold Rule** dialog box is displayed.

5.  You can choose from two types of rules: Compare Constant and Compare Counter. Select the appropriate type and set the values.

    > [!NOTE]
    > Set the **Alert If Over** property to **True** to indicate that exceeding a threshold is a problem, or to **False** to indicate that falling below a threshold is a problem.

## See also

- [Analyzing Threshold Rule Violations](../test/analyze-threshold-rule-violations-in-load-tests.md)
- [Specifying the Counter Sets and Threshold Rules for Computers in a Load Test](../test/specify-counter-sets-and-threshold-rules-for-load-testing.md)
- [Analyze Load Test Results](../test/analyze-load-test-results-using-the-load-test-analyzer.md)
- [Specifying the Counter Sets and Threshold Rules for Computers in a Load Test](../test/specify-counter-sets-and-threshold-rules-for-load-testing.md)