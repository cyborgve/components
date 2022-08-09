## API Report File for "components-srcs"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import { AsyncFactoryFn } from '@angular/cdk/testing';
import { HarnessPredicate } from '@angular/cdk/testing';
import { _MatRadioButtonHarnessBase } from '@angular/material/radio/testing';
import { _MatRadioGroupHarnessBase } from '@angular/material/radio/testing';
import { RadioButtonHarnessFilters } from '@angular/material/radio/testing';
import { RadioGroupHarnessFilters } from '@angular/material/radio/testing';
import { TestElement } from '@angular/cdk/testing';

// @public
export class MatLegacyRadioButtonHarness extends _MatRadioButtonHarnessBase {
    // (undocumented)
    protected _clickLabel: AsyncFactoryFn<TestElement>;
    static hostSelector: string;
    // (undocumented)
    protected _textLabel: AsyncFactoryFn<TestElement>;
    static with(options?: RadioButtonHarnessFilters): HarnessPredicate<MatLegacyRadioButtonHarness>;
}

// @public
export class MatLegacyRadioGroupHarness extends _MatRadioGroupHarnessBase<typeof MatLegacyRadioButtonHarness, MatLegacyRadioButtonHarness, RadioButtonHarnessFilters> {
    // (undocumented)
    protected _buttonClass: typeof MatLegacyRadioButtonHarness;
    static hostSelector: string;
    static with(options?: RadioGroupHarnessFilters): HarnessPredicate<MatLegacyRadioGroupHarness>;
}

export { RadioButtonHarnessFilters }

export { RadioGroupHarnessFilters }

// (No @packageDocumentation comment for this package)

```